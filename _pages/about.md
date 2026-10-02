---
permalink: /
title: "Hyomuk Kim"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<style>
  :root {
    --ucsd-gold: #C69214;
    --title-navy: #0F4C81;
    --text-muted: #666666;
  }
</style>

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">

I am a Master's student in Electrical and Computer Engineering at UC San Diego (graduating March 2027), specializing in Intelligent Systems, Robotics, and Control (EC80). I recently joined the <a href="https://existentialrobotics.org/" style="color: var(--ucsd-gold); font-weight: bold; text-decoration: none;">Existential Robotics Lab</a> (ERL), where I am supervised by Professor <a href="https://natanaso.github.io/" style="color: var(--ucsd-gold); font-weight: bold; text-decoration: none;">Nikolay Atanasov</a>. I am looking for full-time roles in robot perception, SLAM, and robot learning starting in spring 2027.

<details>
  <summary><b style="color: #0F4C81;">Click to expand my past journey</b></summary>
  <br>
  Prior to joining UC San Diego, I was a Staff Engineer at the Robot Center of <a href="https://research.samsung.com"  style="color: var(--ucsd-gold); font-weight: bold; text-decoration: none;">Samsung Research</a>, where I focused on mobile robotic navigation. Working under the guidance of <a href="https://linkedin.com/in/junghyun-kwon"  style="color: var(--ucsd-gold); font-weight: bold; text-decoration: none;">Junghyun Kwon</a> and <strong>Aron Baik</strong>, I specialized in visual SLAM, 3D localization, mapping, and robust motion planning. <br><br>
  My research extends beyond robotics into applied AI. At Samsung's Global AI Center, advised by <a href="https://linkedin.com/in/chanwoo-kim-2628a622" style="color: var(--ucsd-gold); font-weight: bold; text-decoration: none;">Chanwoo Kim</a>, I engineered a Neural Text-To-Speech (TTS) engine—executing the entire pipeline from data collection and model training to C++ deployment. I also contributed to projects involving neural networks for Brain-Machine Interfaces (BMI) and command recommendation engines for AI agents. <br><br>
  Earlier in my career, I built a strong foundation in hardware and product development. I spent 5 years at Samsung's Visual Display Division, validating circuit systems for flagship TVs. Additionally, I led a 6-member team at C-Lab as a Project Manager, spearheading the development of a cross-device content archive platform.
</details>

> For a comprehensive overview of my experience, please refer to my <a href="https://hyomuk-kim.github.io/files/Curriculum-Vitae_Hyomuk-Kim.pdf" style="color: var(--ucsd-gold); font-weight: bold; text-decoration: none;">Curriculum Vitae</a>.

<h2 style="color: var(--title-navy); margin-bottom: 10px;">News</h2>

* **[Apr. 2026]** I have joined the Existential Robotics Laboratory (ERL) for research projects!
* **[Sep. 2025]** I have started my Master’s degree in ECE at UC San Diego!

<h2 style="color: var(--title-navy); margin-bottom: 10px;">Research Interests</h2>

My long-term research goal is to build safe, reliable, and highly adaptable autonomous systems. Specifically, I am interested in blending classic trajectory optimization and visual SLAM with modern robot learning techniques to enable continuous intelligence improvement in complex, unstructured environments.

* **Robot Perception:** Visual SLAM, Sensor Fusion, Semantic Mapping
* **Motion Planning:** Trajectory Optimization (MPPI, MPC), Safe Navigation
* **Robot Learning:** Deep Reinforcement Learning, Generative Models, Embodied AI

<h2 style="color: var(--title-navy); margin-bottom: 10px;">Selected Patents</h2>
Throughout my career as a robotics and hardware engineer at Samsung, I have authored and contributed to multiple patents, two of which have been granted in the US. Below are a few selected works: <br>

* **Robot System as a Mothership and Controller of Microbots.**
  **Hyomuk Kim**, Aron Baik.
  <a href="https://patents.google.com/patent/US20240148213A1/en?oq=WO2023063565A1" style="color: var(--ucsd-gold); font-weight: bold; text-decoration: none;">US20240148213A1</a> (pending), May 2024.
* **Robot Device Operating In Mode Corresponding To Position Of Robot Device And Control Method Thereof.**
  **Hyomuk Kim**, Woojeong Kim, Jewoong Ryu, Mideum Choi, Aron Baik.
  <a href="https://patents.google.com/patent/US12560940B2/en" style="color: var(--ucsd-gold); font-weight: bold; text-decoration: none;">US12560940B2</a> (granted), Feb 2026.
* **Movable Robot And Controlling Method Thereof.**
  Eunsoll Chang, Youngil Koh, **Hyomuk Kim**, Mideum Choi.
  <a href="https://patents.google.com/patent/US20230356391A1/en?oq=US20230356391A1" style="color: var(--ucsd-gold); font-weight: bold; text-decoration: none;">US20230356391A1</a> (pending), Nov 2023.
* **Method of Yield Planning for Mobile Robots.**
  Mideum Choi, **Hyomuk Kim**, Jewoong Ryu, Aron Baik.
  <a href="https://patents.google.com/patent/US12468305B2/en" style="color: var(--ucsd-gold); font-weight: bold; text-decoration: none;">US12468305B2</a> (granted), Nov 2025.

<h2 style="color: var(--title-navy); margin-bottom: 10px;">Projects</h2>

<div style="display: flex; align-items: flex-start; margin-bottom: 40px;">
  <div style="flex: 1;">
    <h3 style="margin-top: 0; margin-bottom: 5px; font-size: 1.25em;"><strong>Long-Horizon Non-Prehensile Manipulation with Sampling-Based MPC</strong></h3>
    <p style="margin-top: 0; margin-bottom: 12px; font-size: 0.9em; color: #666;"><em>Existential Robotics Lab, UC San Diego (Apr 2026 – Present)</em></p>
    <p style="margin-bottom: 12px; line-height: 1.5; font-size: 0.95em;">Research on pushing objects to goal poses among obstacles with an xArm6 manipulator using sampling-based model predictive control. I built the perception pipeline and the real-robot experiment infrastructure. The paper is under review; details will follow after the review period.</p>
    <p style="margin-bottom: 0;"><small><strong>Tech:</strong> MPPI, Perception, Real-Robot Experiments</small></p>
  </div>
</div>

<div style="display: flex; align-items: flex-start; margin-bottom: 40px;">
  <div style="flex: 0 0 180px; margin-right: 25px;">
    <img src="/images/viz_of_visual_slam_in_rviz.jpg" alt="Visual SLAM in RViz" style="width: 100%; aspect-ratio: 1/1; object-fit: contain; border-radius: 8px; border: 1px solid #eaeaea; box-shadow: 0 4px 6px rgba(0,0,0,0.05);">
  </div>
  <div style="flex: 1;">
    <h3 style="margin-top: 0; margin-bottom: 5px; font-size: 1.25em;"><strong>Visual SLAM for Autonomous Mobile Robots</strong></h3>
    <p style="margin-top: 0; margin-bottom: 12px; font-size: 0.9em; color: #666;"><em>Samsung Research (Apr 2021 – Aug 2024)</em></p>
    <p style="margin-bottom: 12px; line-height: 1.5; font-size: 0.95em;">Architected and implemented the visual SLAM module of a new AMR platform in C++, building on the ORB-SLAM3 design: stereo feature matching, pose estimation, and multi-threaded local bundle adjustment with Ceres. It ran under ROS2 on a Qualcomm RB5 with a RealSense D435 and was tested on mobile robots in indoor environments.</p>
    <p style="margin-bottom: 0;"><small><strong>Tech:</strong> C++, ROS2, Ceres, Eigen, OpenCV</small></p>
  </div>
</div>

<div style="display: flex; align-items: flex-start; margin-bottom: 40px;">
  <div style="flex: 0 0 180px; margin-right: 25px;">
    <img src="/images/diffcot_pose_error.png" alt="Pose error of differentiable MPC vs MPPI" style="width: 100%; aspect-ratio: 1/1; object-fit: contain; border-radius: 8px; border: 1px solid #eaeaea; box-shadow: 0 4px 6px rgba(0,0,0,0.05);">
  </div>
  <div style="flex: 1;">
    <h3 style="margin-top: 0; margin-bottom: 5px; font-size: 1.25em;"><strong>Simultaneous System Identification and Control for Object Pushing via Differentiable Physics</strong></h3>
    <p style="margin-top: 0; margin-bottom: 12px; font-size: 0.9em; color: #666;"><em>UC San Diego (Apr 2026 – Jun 2026)</em></p>
    <p style="margin-bottom: 12px; line-height: 1.5; font-size: 0.95em;">Coupled a receding-horizon differentiable MPC with a moving-horizon estimator inside one differentiable MuJoCo MJX model, identifying an object's friction and center of mass online while pushing it to a goal. On an asymmetric L-block, online identification reached the goal where MPPI planning on a wrong model stalled.</p>
    <p style="margin-bottom: 0;"><small><strong>Tech:</strong> JAX, MuJoCo MJX, Differentiable MPC, Moving Horizon Estimation</small></p>
  </div>
</div>

<div style="display: flex; align-items: flex-start; margin-bottom: 40px;">
  <div style="flex: 0 0 180px; margin-right: 25px;">
    <img src="/images/cec_figure_eight.png" alt="Figure-eight tracking with CEC" style="width: 100%; aspect-ratio: 1/1; object-fit: contain; border-radius: 8px; border: 1px solid #eaeaea; box-shadow: 0 4px 6px rgba(0,0,0,0.05);">
  </div>
  <div style="flex: 1;">
    <h3 style="margin-top: 0; margin-bottom: 5px; font-size: 1.25em;"><strong>Safe Trajectory Tracking: Receding-Horizon CEC vs. Generalized Policy Iteration</strong></h3>
    <p style="margin-top: 0; margin-bottom: 12px; font-size: 0.9em; color: #666;"><em>UC San Diego (May 2026 – Jun 2026)</em></p>
    <p style="margin-bottom: 12px; line-height: 1.5; font-size: 0.95em;">Compared online nonlinear MPC (certainty equivalent control in CasADi) with offline generalized policy iteration on an adaptive grid for a differential-drive robot tracking a figure-eight among obstacles. CEC had about 3x lower tracking error and no collisions at 25 ms per step, while GPI controlled the robot with 0.13 ms table lookups.</p>
    <p style="margin-bottom: 0;"><small><strong>Tech:</strong> Python, CasADi, Dynamic Programming, Stochastic Optimal Control</small></p>
  </div>
</div>

<div style="display: flex; align-items: flex-start; margin-bottom: 40px;">
  <div style="flex: 0 0 180px; margin-right: 25px;">
    <img src="/images/rrt_star_maze.png" alt="RRT* path in a 3D maze" style="width: 100%; aspect-ratio: 1/1; object-fit: contain; border-radius: 8px; border: 1px solid #eaeaea; box-shadow: 0 4px 6px rgba(0,0,0,0.05);">
  </div>
  <div style="flex: 1;">
    <h3 style="margin-top: 0; margin-bottom: 5px; font-size: 1.25em;"><strong>Real-Time RRT* Motion Planning in 3D with Moving Goals</strong></h3>
    <p style="margin-top: 0; margin-bottom: 12px; font-size: 0.9em; color: #666;"><em>UC San Diego (Apr 2026 – May 2026)</em></p>
    <p style="margin-bottom: 12px; line-height: 1.5; font-size: 0.95em;">Implemented RRT* for 3D environments with path smoothing and R-tree spatial indexing, and reused the search tree across moving goals instead of rebuilding it. Reached eight sequential goals in about 0.05 s in total and converged to within 0.28 m of the shortest path.</p>
    <p style="margin-bottom: 0;"><small><strong>Tech:</strong> Python, RRT*, R-tree</small></p>
  </div>
</div>

<div style="display: flex; align-items: flex-start; margin-bottom: 40px;">
  <div style="flex: 0 0 180px; margin-right: 25px;">
    <video src="/videos/diffusion_policy.mov" autoplay loop muted playsinline style="width: 100%; aspect-ratio: 1/1; object-fit: cover; border-radius: 8px; border: 1px solid #eaeaea; box-shadow: 0 4px 6px rgba(0,0,0,0.05);"></video>
  </div>
  <div style="flex: 1;">
    <h3 style="margin-top: 0; margin-bottom: 5px; font-size: 1.25em;"><strong>Action Diffusion Policy: Generative Imitation Learning for Manipulation</strong></h3>
    
    <p style="margin-top: 0; margin-bottom: 12px; font-size: 0.9em; color: #666;"><em>UC San Diego (Jan 2026 – Mar 2026)</em></p>
    
    <p style="margin-bottom: 12px; line-height: 1.5; font-size: 0.95em;">Implemented a Conditional Denoising Diffusion Policy using a 1D Temporal U-Net to solve mode-averaging in explicit Behavior Cloning. Achieved an 81.33% success rate on contact-rich manipulation tasks in the Push-T environment by integrating EMA weight smoothing and Action Chunking.</p>
    
    <p style="margin-bottom: 0;"><small><strong>Tech:</strong> PyTorch, Diffusers, Gymnasium, LeRobot</small></p>
  </div>
</div>

<div style="display: flex; align-items: flex-start; margin-bottom: 40px;">
  <div style="flex: 0 0 180px; margin-right: 25px;">
    <img src="/images/vi_slam.png" alt="VI SLAM" style="width: 100%; aspect-ratio: 1/1; object-fit: contain; border-radius: 8px; border: 1px solid #eaeaea; box-shadow: 0 4px 6px rgba(0,0,0,0.05);">
  </div>
  <div style="flex: 1;">
    <h3 style="margin-top: 0; margin-bottom: 5px; font-size: 1.25em;"><strong>6-DOF Visual-Inertial SLAM Using Extended Kalman Filter</strong></h3>
    <p style="margin-top: 0; margin-bottom: 12px; font-size: 0.9em; color: #666;"><em>UC San Diego (Feb 2026 – Mar 2026)</em></p>
    <p style="margin-bottom: 12px; line-height: 1.5; font-size: 0.95em;">Built a VI-SLAM system fusing high-rate IMU SE(3) kinematics with stereo vision using a Full EKF. Optimized the bottleneck via sparse batch updates and analyzed filter limitations against dynamic outliers (e.g., deceptive static objects) in complex datasets.</p>
    <p style="margin-bottom: 0;"><small><strong>Tech:</strong> Python, Lie Algebra, Stereo Vision</small></p>
  </div>
</div>

<div style="display: flex; align-items: flex-start; margin-bottom: 40px;">
  <div style="flex: 0 0 180px; margin-right: 25px;">
    <img src="/images/ekf_slam.png" alt="EKF SLAM" style="width: 100%; aspect-ratio: 1/1; object-fit: contain; border-radius: 8px; border: 1px solid #eaeaea; box-shadow: 0 4px 6px rgba(0,0,0,0.05);">
  </div>
  <div style="flex: 1;">
    <h3 style="margin-top: 0; margin-bottom: 5px; font-size: 1.25em;"><strong>2D LiDAR SLAM & Pose Graph Optimization (PGO)</strong></h3>
    <p style="margin-top: 0; margin-bottom: 12px; font-size: 0.9em; color: #666;"><em>UC San Diego (Feb 2026)</em></p>
    <p style="margin-bottom: 12px; line-height: 1.5; font-size: 0.95em;">Developed a SLAM pipeline for a PR2 robot fusing wheel encoders, IMU, and LiDAR. Implemented 2D ICP for scan-matching and robust PGO using GTSAM with Huber M-estimators to successfully reject false loop closures caused by the aperture problem.</p>
    <p style="margin-bottom: 0;"><small><strong>Tech:</strong> GTSAM, Python, Sensor Fusion</small></p>
  </div>
</div>

<div style="display: flex; align-items: flex-start; margin-bottom: 40px;">
  <div style="flex: 0 0 180px; margin-right: 25px;">
    <video src="/videos/youbot.mp4" autoplay loop muted playsinline style="width: 100%; aspect-ratio: 1/1; object-fit: cover; border-radius: 8px; border: 1px solid #eaeaea; box-shadow: 0 4px 6px rgba(0,0,0,0.05);"></video>
  </div>
  <div style="flex: 1;">
    <h3 style="margin-top: 0; margin-bottom: 5px; font-size: 1.25em;"><strong>Mobile Manipulation Control Pipeline for KUKA youBot</strong></h3>
    <p style="margin-top: 0; margin-bottom: 12px; font-size: 0.9em; color: #666;"><em>UC San Diego (Feb 2026 – Mar 2026)</em></p>
    <p style="margin-bottom: 12px; line-height: 1.5; font-size: 0.95em;">Designed a kinematic software pipeline featuring a task-space feedback controller and an 8-segment trajectory generator for complex pick-and-place tasks. Addressed singularity avoidance, integral windup, and joint velocity saturation.</p>
    <p style="margin-bottom: 0;"><small><strong>Tech:</strong> Python, CoppeliaSim, Kinematics</small></p>
  </div>
</div>

<div style="display: flex; align-items: flex-start; margin-bottom: 40px;">
  <div style="flex: 0 0 180px; margin-right: 25px;">
    <img src="/images/panorama.png" alt="Panorama" style="width: 100%; aspect-ratio: 1/1; object-fit: contain; border-radius: 8px; border: 1px solid #eaeaea; box-shadow: 0 4px 6px rgba(0,0,0,0.05);">
  </div>
  <div style="flex: 1;">
    <h3 style="margin-top: 0; margin-bottom: 5px; font-size: 1.25em;"><strong>3D Orientation Tracking & Panorama Reconstruction</strong></h3>
    <p style="margin-top: 0; margin-bottom: 12px; font-size: 0.9em; color: #666;"><em>UC San Diego (Jan 2026)</em></p>
    <p style="margin-bottom: 12px; line-height: 1.5; font-size: 0.95em;">Formulated an optimization-based state estimator on the unit quaternion manifold using Projected Gradient Descent (PyTorch) to fuse IMU kinematics. Reconstructed panoramic images by mapping pixel coordinates to spherical coordinates using estimated camera poses.</p>
    <p style="margin-bottom: 0;"><small><strong>Tech:</strong> PyTorch, Optimization, Computer Vision</small></p>
  </div>
</div>


<h2 style="color: var(--title-navy); margin-bottom: 10px;">Professional Experiences</h2>

<div style="border-left: 3px solid var(--title-navy); padding-left: 15px; margin-bottom: 20px;">
  <div style="display: flex; justify-content: space-between; align-items: baseline; margin-bottom: 10px;">
    <h3 style="margin: 0; color: var(--title-navy); font-size: 1.2em;">Samsung Research</h3>
    <span style="color: var(--text-muted); font-size: 0.9em;">Seoul, Korea</span>
  </div>
  
  <div style="display: flex; justify-content: space-between; align-items: baseline; margin-bottom: 6px;">
    <div><strong>Staff Engineer (Robotics)</strong> <span style="color: var(--text-muted); font-size: 0.95em;">| Robot Intelligence Team</span></div>
    <span style="font-size: 0.85em; color: var(--text-muted);">Apr. 2021 – Aug. 2024</span>
  </div>
  
  <div style="display: flex; justify-content: space-between; align-items: baseline; margin-bottom: 6px;">
    <div><strong>Engineer (Deep Learning)</strong> <span style="color: var(--text-muted); font-size: 0.95em;">| Global AI Center</span></div>
    <span style="font-size: 0.85em; color: var(--text-muted);">Jan. 2020 – Apr. 2021</span>
  </div>
  
  <div style="display: flex; justify-content: space-between; align-items: baseline; margin-bottom: 0;">
    <div><strong>Engineer (Deep Learning)</strong> <span style="color: var(--text-muted); font-size: 0.95em;">| Language & Voice Team</span></div>
    <span style="font-size: 0.85em; color: var(--text-muted);">Apr. 2018 – Jan. 2020</span>
  </div>
</div>

<div style="border-left: 3px solid var(--title-navy); padding-left: 15px; margin-bottom: 20px;">
  <div style="display: flex; justify-content: space-between; align-items: baseline; margin-bottom: 10px;">
    <h3 style="margin: 0; color: var(--title-navy); font-size: 1.2em;">Samsung Electronics</h3>
    <span style="color: var(--text-muted); font-size: 0.9em;">Suwon, Korea</span>
  </div>
  
  <div style="display: flex; justify-content: space-between; align-items: baseline; margin-bottom: 6px;">
    <div><strong>Project Leader</strong> <span style="color: var(--text-muted); font-size: 0.95em;">| C-Lab</span></div>
    <span style="font-size: 0.85em; color: var(--text-muted);">Jun. 2014 – Jun. 2015</span>
  </div>
  
  <div style="display: flex; justify-content: space-between; align-items: baseline; margin-bottom: 0;">
    <div><strong>Engineer (Circuit Design)</strong> <span style="color: var(--text-muted); font-size: 0.95em;">| TV R&D Lab</span></div>
    <span style="font-size: 0.85em; color: var(--text-muted);">Apr. 2013 – Apr. 2018</span>
  </div>
</div>
