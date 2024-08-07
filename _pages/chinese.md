---
layout: archive
title: "关于我"
permalink: /chinese/
author_profile: true
---

{% include base_path %}

你好！我是**许志强**（Niko）。

我目前是西北工业大学的人工智能硕士二年级在读生。我对于做有意义的人工智能研究有着强烈的热情，我的研究兴趣包括智能决策（强化学习）、机器人技术、多智能体系统和具身智能等。

在学术生活之外，我对心理学很感兴趣，并且喜欢徒步旅行、打羽毛球和游泳。

<span style="color:red"><b>[Highlight]</b></span> 我目前在寻找一个**研究实习/RA**的职位，如果您有任何意向或线索，请邮件联系 nikohsu@qq.com ，谢谢！

教育背景
======
09/2022 至 04/2025：西北工业大学(985)，人工智能，硕士，西安。

09/2017 至 06/2022：广西大学(211)，自动化，本科，南宁。

- GPA：3.32（专业排名第5/132）

07/2018 至 08/2018: 暑期学校, [加州大学洛杉矶分校(UCLA)](https://www.ucla.edu/), 洛杉矶.

- 主修课程: 学术写作,  研究范式,  跨文化交流等

项目经历
======
note: 部分项目无法公开图片，未作展示

- **基于强化学习的室内机器人自主导航**

面向端到端的室内家庭机器人智能需求，针对真实环境中的强化学习训练缺少真值数据的问题，设计强化学习算法实现机器人自主室内导航，通过训练，机器人可以学习在不同类型的障碍物中选择绕过或推动障碍物以更快地到达目的地。

<img src="/page/images/PJ_navigation.gif" alt="nav" width="400" height="240">

- 与中国移动杭州研究院合作研究，实习考核优秀（优秀率约30%）；
- 使用PPO算法，实现基于纯视觉输入的自主导航（具身智能）；
- 视觉图像输入包括RGB图像和深度图像；
- 仿真环境来源于斯坦福大学斯坦福SVL Lab的[igibson](https://svl.stanford.edu/igibson/)环境；


- **基于视觉的四旋翼飞行器目标跟踪**

对于追踪目标下一步动作未知以及机载传感图像存在运动模糊等难题，基于运动模糊去卷积的图像预处理算法作为目标识别的前处理，并基于误差状态卡尔曼滤波（ESKF），根据当前状态估计和IMU测量相融合，对目标位置进行融合估计，实现给定未知目标的追踪。

<img src="/page/images/PJ_uavtrack.gif" alt="Tracking" width="400" height="240">
<img src="/page/images/PJ_SPtrack.gif" alt="Tracking2" width="240" height="400">

- 基于视觉传感器进行目标检测，基于ESKF对目标位置进行融合估计；
- 利用自适应控制算法实现四旋翼飞行器对目标的跟踪；
- 图像处理算法、目标检测网络和控制算法部署于Jetson Nano。

- **智能车(算法，软件，硬件全栈)**

基于比赛对智能车以尽快的速度自主穿越复杂地形的要求，从物理架构，软件，硬件和算法层面完成整车设计。

<img src="/page/images/PJ_nxpcar.gif" alt="nxpcar" width="400" height="240">

- 基于包括摄像头和电磁传感器在内的多种传感器；
- 嵌入式图像和数据处理算法，自动巡线和控制算法；
- 主控电路以及电机驱动电路；
- 使用NXP K60 MCU构建控制器。

- **基于强化学习的多无人机编队机动控制**

对于多智能体以及智能体空中动作极多导致的的动作维度爆炸，进而导致训练及收敛困难的难题，设计了动态目标分配算法，决策树剪枝等手段，通过降低维度，共享经验等手段，提高模型训练收敛速度，实现多无人机编队机动控制。

<img src="/page/images/PJ_UAV2v2.gif" alt="uav" width="400" height="240">

- 基于强化学习中的MAPPO算法；
- 基于[JSBSIM飞行仿真器](https://jsbsim.sourceforge.net/)的动力学模型；
- 实现多个无人机的自主智能决策。

论文
======
- **Approximate Optimal Strategy for Multi-Agent System Pursuit-Evasion Game** [[Paper]](https://ieeexplore.ieee.org/document/10621746/)

**First author**, [IEEE Systems Journal](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=4267003). 2024

<img src="/page/images/PA_PE-game.png" alt="mpe" width="400" height="150">

针对目前多智能体系统追逃博弈过程中，单组智能体内部缺少团队凝聚力的难题，我们提出了一种用于非线性多智能体系统追逐逃避（MPE）博弈的近似最优控制策略，通过图论方法、动态目标图算法以及Hamilton-Jacobi-Isaacs (HJI) 方程的求解策略，有效增加了智能体集群的团队协作，并通过仿真和对比实验验证了算法的有效性。


- **PSEF: Point Cloud and Semantic-Based ESKF Fusion System for Precise Underground Parking Enviroment Localization**

**First author**, [IEEE Sensors Journal](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=7361), Under Review.

地下停车环境带来了诸多挑战，如无GPS信号、照明不佳和复杂环境干扰，导致传感器定位不精确和不稳定。为了解决这些问题，我们提出了一种基于双层地图匹配和融合的PSEF系统。我们构建了基于激光雷达里程计的点云地图和基于相机数据和语义分割的语义地图，并首次引入了基于ESKF的点云和语义信息的融合，在仿真系统中实现了较高精度的定位。

开源数据集网址: [https://github.com/NikoHsu/PSEF_Localization_dataset](https://github.com/NikoHsu/PSEF_Localization_dataset).

<img src="/page/images/slam.png" alt="slam" width="300" height="600">

<img src="/page/images/slam2.jpg" alt="slam2" width="333" height="200">

（a）当前帧的BEV图像。（b）车辆前视图。（c）双层地图融合图解。


技能
======
口语：英语（流利，CET4 562，CET6 514）、普通话（母语）、德语（基础，歌德A1）

编程语言：C/C++、Matlab、Python、LaTeX

工具：Linux、ROS、Git

荣誉和奖项（部分）
======
- 全国大学生电子设计竞赛一等奖（2020）

[项目展示：3天内实现并搭建 简易无接触温度测量与身份识别装置](https://www.bilibili.com/video/BV1ZK4y177U2)

- “深圳杯”数学建模挑战赛三等奖（2020）

- 全国大学生智能汽车竞赛南方赛区三等奖（2020）

- “互联网+”大学生创新创业大赛省金奖&全国铜奖（2021）

- 全国大学生数学竞赛省一等奖（2021）

- “三航杯”科技作品竞赛一等奖（2023/2024）
 
- 华为昇腾 AI 创新大赛省赛金奖 & 全国铜奖（2023）

- 多次获得广西大学优秀学生奖学金等（2019/2020/2021）

Visitor Map
------

<script type="text/javascript" src="//rf.revolvermaps.com/0/0/6.js?i=54e0ojatafc&amp;m=7&amp;c=e63100&amp;cr1=ffffff&amp;f=arial&amp;l=0&amp;bv=90&amp;lx=-420&amp;ly=420&amp;hi=20&amp;he=7&amp;hc=a8ddff&amp;rs=80" async="async"></script>
