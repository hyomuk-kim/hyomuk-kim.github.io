---
title: "Visual Navigation"
excerpt: "Visual SLAM with multiple cameras (ongoing)  <br/><img src='/images/500x300.png'>"
collection: portfolio
---

> _Since it's an ongoing project, please understand that I may not be able to provide detailed explanations here due to security concerns._

This project's objective is to create a in-house visual SLAM module for small home robots and factory robots.

A need for a solution enabling visual-only autonomous navigation, distinct from an existing 2D LiDAR solution, has been emerged with considerations for size and design of robot's body. Camera is design-friendly sensor because it has simpler structure and even cheaper price than LiDAR. Furthermore, visual information from cameras can be used for map reconstruction and pose estimation for 3D environment. Meanwhile, given the embedded platform's performance limitations, we have leaned toward classical algorithms.

In response to these requirements, we designed the generalized Visual SLAM architecture after benchmarking various algorithms.
This module is a basically feature-based and it consists of visual odometry, local bundle adjustment, map management and pose graph optimization. We introduced a extended structure to cope with multiple sensor configuration in the light of scalability.

This module processes image topics from cameras via a ROS2 node, extracts features from image pyramid, matches them for tracking based on descriptors, and optimizes pose using a cost function for reprojection errors and an initial estimate from wheel odometry with variable weight. This process yields a sparse map and estimates the robot's 6 degrees of freedom pose.

To evaluate the module, we collects rosbag data recorded by our robot, which simulates a variety of situations occuring in indoor environments, and we measures root mean square error(RMSE) for robot's trajectory and compares it with ground truth.