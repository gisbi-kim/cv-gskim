More recent news are found here https://bit.ly/giseopkim

<br><br/>
# Giseop KIM (김기섭)

## Summary 
- I am a **SLAM researcher/engineer**. My research interests are state estimation and 3D perception for autonomous robots.
- My main research topic during the Ph.D. has been focused on **robust 3D mapping in complex urban sites using LiDAR sensors**. 
- I have experience in **a full pipeline of SLAM** in the real world (e.g., from sensor fusion, calibration, odometry, place retrieval, pose-graph optimization, multi-session localization, to long-term map management).

## My Channels 
  - :envelope: Mail: paulgkim@kaist.ac.kr 
  - :computer: Github: [gisbi-kim](https://github.com/gisbi-kim) 
  - :tv: Youtube: [bit.ly/giseopkim-youtube](https://bit.ly/giseopkim-youtube)

## Education 
- Korea Advanced Institute of Science and Technology (KAIST) — Feb 2022 (expected)
  - Ph.D. in Civil and Environmental Engineering (CEE) 
  - Dissertation: *"LiDAR-based Lifelong Robotic Mapping in Changing Environments"*
  - Advisor: Dr. Ayoung Kim and Dr. Youngchul Kim
- Korea Advanced Institute of Science and Technology (KAIST) — Feb 2019
  - M.S. in Civil and Environmental Engineering (CEE) 
  - Dissertation: *"Isovist-induced Robust LiDAR Localization"*
  - Advisor: Dr. Ayoung Kim
- Korea Advanced Institute of Science and Technology (KAIST) — Feb 2017
  - B.S. in Civil and Environmental Engineering (CEE) 

## Selected Publications 
### 2021
  - **Giseop Kim** and Ayoung Kim. *“LT-mapper: A Modular Framework for LiDAR-based Lifelong Mapping.”* arXiv abs/2107.07712 (2021), Submitted to 2022 IEEE International Conference on Robotics and Automation (ICRA) and Under Review (2022).
  - **Giseop Kim**, Sunwook Choi, and Ayoung Kim. *“Scan Context++: Structural Place Recognition Robust to Rotation and Lateral Variations in Urban Environments.”* Submitted to IEEE Transactions on Robotics and Under Review (2021).
### 2020 
  - **Giseop Kim** and Ayoung Kim. *“Remove, then Revert: Static Point cloud Map Construction using Multiresolution Range Images.”* 2020 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS) (2020): 10758-10765.
  - **Giseop Kim**, Yeong-Sang Park, Younghun Cho, Jinyong Jeong and Ayoung Kim. *“MulRan: Multimodal Range Dataset for Urban Place Recognition.”* 2020 IEEE International Conference on Robotics and Automation (ICRA) (2020): 6246-6253.
  - Younggun Cho, **Giseop Kim** and Ayoung Kim. *“Unsupervised Geometry-Aware Deep LiDAR Odometry.”* 2020 IEEE International Conference on Robotics and Automation (ICRA) (2020): 2145-2152.
### 2019
  - **Giseop Kim**, Byungjae Park and Ayoung Kim. *“1-Day Learning, 1-Year Localization: Long-Term LiDAR Localization Using Scan Context Image.”* IEEE Robotics and Automation Letters 4 (2019): 1948-1955 (with ICRA 2019).
  - **Giseop Kim**, Ayoung Kim and Youngchul Kim. *“A new 3D space syntax metric based on 3D isovist capture in urban space using remote sensing technology.”* Comput. Environ. Urban Syst. 74 (2019): 74-87.
### 2018
  - **Giseop Kim** and Ayoung Kim. *“Scan Context: Egocentric Spatial Descriptor for Place Recognition Within 3D Point Cloud Map.”* 2018 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS) (2018): 4802-4809.

## Previous Positions 
- Graduate Student Research Assistant — Mar. 2017 - Aug. 2021
  - Intelligent Robotic Autonomy and Perception (IRAP) lab, Dept. of Civil and Environmental Engineering, KAIST, South Korea.

## Projects
**Note**
- All projects had been done at IRAP lab of KAIST as Graduate Student Research Assistant.  
- The date of the accumulated Cited📰 and Github⭐ counts is **2021.09.06**.

### 1) Dataset Generatation 
  - **MulRan: Multimodal Range dataset**
    - tldr: LiDAR + Radar dataset for place recognition evaluations in complex urban sites.
    - role: 1st-author of the paper who conducted all experiments, a project manager who led data acquisitions and manages the dataset site. 
    - key result and achievement: paper ([ICRA 2020](https://gisbi-kim.github.io/publications/gskim-2020-icra.pdf) 📰32) and website (https://sites.google.com/view/mulran-pr/home)
   
### 2) Constructing Robust Real-time Range sensor-based SLAM system
  - **Place recognition for range sensors**
    - tldr: A fast, versatile, and robust global localizer for various lidar sensors, named Scan Context.
    - role: 1st-author of the paper who conducted all experiments, the writer of whole codes (C++, Matlab, Python).
    - key result and achievement: papers ([IROS 2018](https://gisbi-kim.github.io/publications/gkim-2018-iros.pdf) 📰81, [RA-L 2019](https://gisbi-kim.github.io/publications/gkim-2019-ral.pdf) 📰45) and codes ([irapkaist/scancontext](https://github.com/irapkaist/scancontext) ⭐342)
  - **Complete LiDAR SLAM systems**
    - tldr: Plug-and-play loop detection and robust pose-graph SLAM that integrated Scan Context and existing LiDAR odomerty methods to build globally consistent 3D point cloud maps in urban sites. 
    - role: I made place recognition (PR) and pose graph optimization (PGO) codes (C++), except the existing the odometry codes. I supported seamless integration of odometry module and PR+PGO module which supports ROS-based interface.     
    - key result and achievement: codes ([irapkaist/SC-LeGO-LOAM](https://github.com/irapkaist/SC-LeGO-LOAM) ⭐427, [gisbi-kim/SC-LIO-SAM](https://github.com/gisbi-kim/SC-LIO-SAM) ⭐215, [gisbi-kim/SC-A-LOAM](https://github.com/gisbi-kim/SC-A-LOAM) ⭐97, [gisbi-kim/FAST_LIO_SLAM](https://github.com/gisbi-kim/FAST_LIO_SLAM) ⭐58)
  - **Complete Radar SLAM systems** 
    - tldr: Urban radar mapping by combining radar Scan Context + radar odometry  
    - role: equal to the above LiDAR SLAM systems
    - key result and achievement: codes ([gisbi-kim/navtech-radar-slam](https://github.com/gisbi-kim/navtech-radar-slam) ⭐36)

### 3) 3D Map Management/Update in High/Low Dynamic Environments
  - **Removert**
    - tldr: make static map, remove dynamic points, and parse dynamic objects in the wild. 
    - role: 1st-author of the paper who conducted all experiments, the writer of the above C++ codes.
    - key result and achievement: paper ([IROS 2020](https://gisbi-kim.github.io/publications/gskim-2020-iros.pdf) 📰8) and codes ([irapkaist/removert](https://github.com/irapkaist/removert) ⭐136)
  - **LT-mapper**
    - tldr: A modular framework for LiDAR-based lifelong mapping. The first long-term LiDAR mapping open source project.  
    - role: 1st-author of the paper who conducted all experiments, the writer of the above C++ codes.
    - key result and achievement: paper ([arXiv 2021](https://arxiv.org/abs/2107.07712)) and codes ([gisbi-kim/lt-mapper](https://github.com/gisbi-kim/lt-mapper) ⭐61)
 
### 4) SLAM tutorials for Beginners
  - **Python tutorial**
    - tldr: Python-only hands-on experiences for introduction to SLAM
    - role: The writer of the Python codes.
    - key result and achievement: codes ([gisbi-kim/PyICP-SLAM](https://github.com/gisbi-kim/PyICP-SLAM) ⭐188, [gisbi-kim/modern-slam-tutorial-python](https://github.com/gisbi-kim/modern-slam-tutorial-python) ⭐26)
- **Youtube videos**
    - tldr: The video-based tutorials to play and enjoy above open SLAM systems are available via my :tv:Youtube
    - role: The maker of the tutorial videos.
    - key result and achievement: videos ([bit.ly/giseopkim-youtube](https://bit.ly/giseopkim-youtube))

## Services 
- Reviewer
  - Journals: T-RO (21), RA-L (21), IJRR (20)
  - Conferences: ICRA (21, 20), IROS (21, 20, 19), UR (21, 20)
- Teaching Assistant
  - 2020 Spring: CE481 (Sensor-based spatial intelligence, a.k.a SLAM 101), CEE, KAIST
  - 2016 Spring: CE352 (Signal and System for Construction IT), CEE, KAIST

## Awards 
- 2019: ICRA 2019 RAS Travel Grant
- 2018: Best paper award at ICRA 2018 workshop of LTA (Long-term autonomy and deployment of intelligent robots in the real-world)

## Skills
- Tools: I am familiar with using C/C++ and Ubuntu/ROS/Ceres/GTSAM/PCL/OpenCV/Eigen/etc.
- Languages: Korean (native), English (fluent)

---
last modified: 2021.09.06
