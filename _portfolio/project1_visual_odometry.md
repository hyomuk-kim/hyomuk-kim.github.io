---
title: "Visual Navigation"
excerpt: " <b>Feature-based Visual Odometry with stereo camera</b>"
collection: portfolio
---
<!-- <br/><img src='/images/500x300.png'> -->

> Info.  
  _Jan. 2022 ~ Present at Robot Intelligence Team with 3 members._

> Note  
  _Since this is an ongoing project, please understand that I can only provide a somewhat abstract description and cannot go into detailed explanations here due to security concerns._

### Goal

The aim of this project is to develop an in-house visual SLAM module for small home robots and factory robots.

### Need

There is a growing need for a solution that enables visual-only autonomous navigation, which is distinct from the existing 2D LiDAR solution. This need has arisen with considerations for the size and design of the robot's body. The camera is a design-friendly sensor because it has a simpler installation structure compared to the 2D rotating LiDAR. Additionally, visual information from cameras can be used for map reconstruction and pose estimation in a 3D environment. However, due to the performance limitations of the embedded platform, we have leaned towards using classical algorithms.

### Approach

To meet these requirements, we designed the generalized and lightweight Visual SLAM architecture after evaluating various algorithms such as ORB-SLAM, Kimera and VINS. This module is fundamentally feature-based and includes components such as visual odometry, local bundle adjustment, map management, and pose graph optimization. We introduced an extended structure to accommodate multiple sensor configurations.

This module processes image data from cameras through a ROS2 node, extracts features from an image pyramid, matches them for tracking based on descriptors, and optimizes the pose using a cost function for reprojection errors with the automatic differentiation of Ceres or analytical derivatives. In cases where the number of feature points is too low or optimization fails, the estimated pose from wheel odometry can optionally be used based on a certain weight. This process results in the creation of a sparse point clouds map (not being used for planning as of now) and provides an estimate of the robot's pose in 6 degrees of freedom.

To evaluate the module, we collected rosbag data recorded by our robot, simulating a variety of situations occurring in indoor environments. We measured the root mean square error (RMSE) for the robot's trajectory and compared it with the ground truth.

### Insights & Further Considerations

* It was crucial that the features tracked from each keyframe to the following frames could robustly match and persist across them. To ensure this, accurate temporal matching for the same features across multiple frames was essential. Therefore, we closely examined the process to achieve robust descriptor matching and had to address and improve problematic factors.

* Previously, the structure was such that map points generated based on features were embedded within individual frames. To continuously update these map point positions to more accurately reflect their estimated depth as the number of frames observing them increased, a structural change was needed to facilitate global map management. This depth update is expected to prevent errors from accumulating in map points and improve the accuracy of the optimization process and pose estimation based on this reliable map.

* A local bundle adjustment module was devised based on local keyframes window. Given our preference for a modular and non-circular structure, the visual odometry and local bundle adjustment modules initially exchanged keyframes and map points through a ROS2 node. This led to difficulties in sharing the optimized map between modules and inefficient data exchange between them. Consequently, we integrated these two modules into one, allowing them to operate in a multi-threaded manner, through which we modified the process so that the addition of new map points and subsequent updates would occur within a single global map.

* While initially considering only a rectified stereo camera, we are currently expanding our sensor framework to include multiple cameras. Additionally, even though we have already implemented the frontend, which includes visual odometry and local bundle adjustment, we are actively working to incorporate insights like the ones mentioned above to create a comprehensive visual SLAM module.

* We eventually intend to ensure that the resulting map can be utilized for planning and can integrate semantic information into the map. To achieve this, we aim to work it up into a denser and more structured 3D map. As part of this, we are exploring various approaches, such as integrating different features like edges dynamically to handle featureless scenes and implementing an effective loop closing method to maintain a stable and consistent map.
