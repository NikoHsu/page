---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hello! Here is **Zhiqiang Hsu (Niko)**.

I'm currently a second-year graduate student pursuing my Master's degree at [Northwestern Polytechnical University](https://www.nwpu.edu.cn/). I have a strong passion for conducting meaningful artificial intelligence research. My research interests encompass Intelligent Decision-making(Reinforcement Learning), Robotics, Multi-agent Systems and Embodied AI. 

Outside of my academic life, I am an enthusiast of psychology and enjoy hiking, badminton and swimming.

<span style="color:red"><b>[Highlight]</b></span> I am currently seeking a visiting student/ Phd position. If you have any leads or opportunities, please contact me via email at nikohsu@qq.com. Thank you!

Education
======
09/2022 ~ 04/2025: M.S.  in Artificial Intelligence, [Northwestern Polytechnical University (985)](https://www.nwpu.edu.cn/), Xian.

09/2017 ~ 06/2022: B.Sc. in Automation, [GuangXi University (211)](https://www.gxu.edu.cn/), Nanning.

- GPA: 3.32  (Rank 5st / 132 in the major)


07/2018 ~ 08/2018: Summer School, [University of California,  Los Angeles (UCLA)](https://www.ucla.edu/), Los Angeles.

- Course Project: Academic Writing,  Research Paradigms,  Intercultural Communication,  etc.


Project Experience
======
- **Robot indoor autonomous navigation based on reinforcement learning**

Facing the demand for end-to-end indoor home robot intelligence, and addressing the challenge of insufficient ground truth data for reinforcement learning training in real-world environments,  we design a reinforcement learning algorithm to achieve autonomous indoor navigation for robots. Through training, the robot can learn to decide whether to navigate around or push obstacles to reach the destination faster in the presence of different types of obstacles.

<!-- ![nav](/page/images/PJ_navigation.gif) -->

<img src="/page/images/PJ_navigation.gif" alt="nav" width="400" height="240">

- Using the PPO algorithm, achieving autonomous navigation based on purely visual input (**Embodied intelligence**);
- Visual image input includes RGB images and depth images.;
- The simulation environment is sourced from the [igibson](https://svl.stanford.edu/igibson/) by Stanford Vision and Learning Lab;

- **Target Tracking for Vision-based Quadcopters**

For the challenges of unknown next actions of the tracked target and motion blur in onboard sensor images, motion deblurring method is used as a preprocessing step for object detection. Additionally, based on Error State Kalman Filter (ESKF), fusion is performed between the current state estimate and IMU measurements to estimate the target position, achieving the tracking of given unknown targets.

<img src="/page/images/PJ_uavtrack.gif" alt="Tracking" width="400" height="240">

<img src="/page/images/PJ_SPtrack.gif" alt="Tracking2" width="240" height="400">

- Using visual sensors for target detection and fusing estimates of target position based on ESKF;
- Tracking of targets by quadcopter using adaptive control algorithm;
- Image processing algorithm, target detection network and control algorithm are deployed on the Jetson Nano.


- **Intelligent unmanned car**

Based on the competition's requirement for intelligent vehicles to autonomously navigate complex terrain as quickly as possible, the entire vehicle design was completed from the perspectives of physical architecture, software, hardware, and algorithms.

<img src="/page/images/PJ_nxpcar.gif" alt="nxpcar" width="400" height="240">

- Based on multiple sensors including cameras and electromagnetic sensors;
- Embedded image and data processing algorithms, automatic line-following and control algorithms;
- Main control circuitry as well as motor drive circuitry;
- Controller built using the NXP K60 MCU;

- **Reinforcement learning for multiple UAVs formation maneuver control**

Addressing the challenge of dimension explosion in training and convergence difficulty caused by the high degree of aerial maneuvers in multi-agent systems, dynamic target allocation algorithms and decision tree pruning methods were designed. By reducing dimensions and sharing experiences, the training convergence speed of the model is improved, achieving multi-drone formation maneuver control.

<img src="/page/images/PJ_UAV2v2.gif" alt="uav" width="400" height="240">

- Based on the MAPPO algorithm in reinforcement learning;
- Dynamics based on [JSBSIM flight simulator](https://jsbsim.sourceforge.net/);
- Implementing autonomous intelligent decision-making for multiple UAVs;


Publications
======
- **Approximate Optimal Strategy for Multi-Agent System Pursuit-Evasion Game**

**Zhiqiang Xu**, Dengxiu Yu, Yan-jun Liu and Zhen Wang. [IEEE Systems Journal](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=4267003). 2024. 

<img src="/page/images/PA_PE-game.png" alt="mpe" width="400" height="150">

We proposes an approximate optimal control strategy for nonlinear Multi-Agent System Pursuit-Evasion (MPE) games, enhancing team coordination through a graph-theoretic approach, dynamic target graph algorithm, and solving strategies using Hamilton-Jacobi-Isaacs (HJI) equations, with validation through simulations.

- **PSEF: Point Cloud and Semantic ESKF Fusion System For Precise and Robust Localization in Underground Parking Environment**

**Zhiqiang Xu**, Kun Gong, Zhaoxiang Zhang and Yuelei Xu. [IEEE Sensors Journal](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=7361), Under Review.

Underground parking environments pose challenges such as GNSS denied, poor lighting and complex interference, resulting in degraded and unstable sensor localization. To address these issues,  We propose a novel system, named PSEF, which is based on dual-layer map matching and fusion. We construct a point cloud map based on LiDAR odometry and a semantic map based on camera data and semantic segmentation. For the first time, we introduce the fusion of point cloud and semantic information based on ESKF.

Open-source dataset URL: [https://github.com/NikoHsu/PSEF_Localization_dataset](https://github.com/NikoHsu/PSEF_Localization_dataset).

<img src="/page/images/slam.png" alt="slam" width="300" height="600">

<img src="/page/images/slam2.jpg" alt="slam2" width="333" height="200">

(a)Current frame’s BEV image. (b) The front view of the vehicle. (c) Illustration of dual-Layer map fusion.

  
Skills
======
Spoken language: English(Fluent), Mandarin(Native), Deutsch(Basic)

Programming Languages: C/C++, Matlab, Python, LaTeX

Tools : Linux, ROS, Git


Honors and Awards(Selected)
======
- First Prize in the National College Students' Electronic Design Competition (2020) [Project display](https://www.bilibili.com/video/BV1ZK4y177U2)

- Third Prize in the "Shenzhen Cup" Mathematical Modeling Challenge (2020)

- Third Prize in the National College Students' Intelligent Car Competition, Southern Region (2020)

- Provincial Gold Award and National Bronze Award in the "Internet Plus" College Student Innovation and Entrepreneurship Competition (2021)

- First Prize in the National College Students' Mathematics Competition (2021)

- Provincial Gold Award and National Bronze Award in the National Finals of the Huawei Ascend AI Innovation Competition (2023)

- First Prize in the "Sanhang Cup" Science and Technology Works Competition (2023/2024)

- Recipient of multiple GXU Outstanding Student Scholarships, etc. (2019/2020/2021)



Visitor Map
------

<script type="text/javascript" src="//rf.revolvermaps.com/0/0/6.js?i=54e0ojatafc&amp;m=7&amp;c=e63100&amp;cr1=ffffff&amp;f=arial&amp;l=0&amp;bv=90&amp;lx=-420&amp;ly=420&amp;hi=20&amp;he=7&amp;hc=a8ddff&amp;rs=80" async="async"></script>
