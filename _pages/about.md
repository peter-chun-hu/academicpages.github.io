---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
# About
---
I am a master student in Electrical and Computer Engineering department at University of California San Diego. I received my bachelor degree from National Taiwan University. My area of interests are robotics and artificial intelligence.
<br><br>

# CV
---
**Education**
* M.Sc., University of California, San Diego - Sep 2017 ∼ May 2019 (expected)
  * Eletrical and Computer Egineering, GPA: 3.7/4.0
  * Relevant Courses: Sensing & Estimation in Robotics, Computer Vision
* B.Sc., National Taiwan University - Sep 2012 ∼ Jun 2016
  * Computer Science and Information Engineering, major GPA: 4.03/4.3  
  * Relevant Courses: Robot Perception & Learning, Machine Learning  

**Work experience**
* Software Intern, TetraVue - Jul 2018 ∼ Sep 2018
  * Developed software to fuse data from various sensors to aid in SLAM
  * Estimated camera position and orientation (visual inertial odometry) using VINS-Mono (a Monocular Visual-Inertial State Estimator) with camera and IMU data
  * Reduced 90% of the camera calibration reprojection error by increasing the search window in OpenCV cornerSubPix function to half the size of the checkerboard square
  * Calibrated stereo camera to get translation and rotation matrices between two cameras and calculate homography matrix to help in stitching images
  * Generated rosbag file (a serialized sensor data file used in robotics operating system robot simulation)
* Research Assistant, National Taiwan University - Sep 2016 ∼ Aug 2017
  * Built physical therapy assisting functions on biped robots including human motion imitation system and balancing algorithms
  * Implemented balancing algorithm to keep the robot from falling when imitating people doing Tai Chi 

**Related experience**
* [Raspberry Pi Car](https://github.com/peter-chun-hu/291d_hw3_ros_src) - C++
  * Detected ArUco markers and built a map with markers’ position and orientation using robotics operating system (ROS) packages
  * Designed an algorithm for robot vacuums to avoid obstacles and plan a path
* [Reinforcement learning](https://github.com/peter-chun-hu/A2C_experience_repaly) - Python
  * Implemented advantage actor-critic (A2C) method in Pytorch and tested in OpenAI Gym environments
  * Incorporated A2C with experience replay to increase the convergence speed
* [Kaggle Humpback Whale Identification Challenge](https://github.com/peter-chun-hu/ECE285_finalproject_TaiwanNo1) - Python
  * Built algorithms to identify whale species using whale tail images
  * 135th of 494 (beating the benchmark)
  * Handled imbalance data by using resampling techniques and modifying the loss function
  * Implemented Siamese network in Keras to calculate image similarity for classification
* [Simultaneous localization and mapping (SLAM)](https://github.com/peter-chun-hu/SLAM) - Python
  * Implemented a particle ﬁlter to track a robot’s pose using IMU, odometry and laser measurements
  * Built 2D occupancy grid maps of the environment using the results of the particle ﬁlter
* [Panorama](https://github.com/peter-chun-hu/Panorama) - Python
  * Implemented unscented Kalman ﬁlter (UKF) to estimate the camera orientation using IMU reading
  * Generated panoramic images by stitching camera images based on the UKF estimation results
* 3D Point Cloud Object - C++
  * Built a stuffed toy 3D model with Point Cloud Library (PCL) Iterative Closest Point (ICP) function

**Skills**
* Programming Languages: C/C++, Python, MATLAB
* Operating Systems: Linux (ubuntu), ROS, Windows
