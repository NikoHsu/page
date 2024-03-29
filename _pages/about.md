---
permalink: /
title: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


Hello! I'm currently a second-year graduate student pursuing my Master's degree at [Northwestern Polytechnical University](https://www.nwpu.edu.cn/). I have a strong passion for research in the field of artificial intelligence. My research interests encompass Intelligent Decision-making(Reinforcement Learning), Robotics, Multi-agent Systems and Embodied AI. 

Outside of my academic life, I am an enthusiast of psychology and enjoy hiking, badminton and swimming.

Education
======
09/2022 ~ Present: Master, [Northwestern Polytechnical University](https://www.nwpu.edu.cn/), Xian.

09/2017 ~ 06/2022: B.Sc. in Control Engineering (Automation), [GuangXi University](https://www.gxu.edu.cn/), Nanning.

GPA: 3.32  (Rank 5st / 132 in the major)

Project Experience
======
- **Autonomous Driving Car**

![nxpcar](/Niko.github.io/images/PJ_nxpcar.gif)

- Based on multiple sensors including cameras and electromagnetic sensors;
- Controller built using the NXP K60 MCU;
- Embedded image and data processing algorithms, automatic line-following and control algorithms;
- Main control circuitry as well as motor drive circuitry;
- It can adapt to various types of roads and park in garages. 

- **Reinforcement learning for multiple UAVs formation decision-making**

![uav](/Niko.github.io/images/PJ_UAV2v2.gif)

- Based on the MAPPO algorithm in reinforcement learning;
- JSBSIM flight simulator;
- Implementing autonomous intelligent decision-making for multiple UAVs;

- **Robot navigation and event handling based on reinforcement learning**

![nxpcar](/Niko.github.io/images/PJ_navigation.gif)

- Using the PPO algorithm, achieving autonomous navigation based on purely visual input (**Embodied intelligence**);
- Visual image input includes RGB images and depth images.;
- The simulation environment is sourced from the [igibson environment](https://svl.stanford.edu/igibson/) by Stanford Vision and Learning Lab;
- Through training, the robot can learn to decide whether to navigate around or push obstacles to reach the destination faster in the presence of different types of obstacles.

Preprints
======
- **paper1**

[![Video Title](https://raw.githubusercontent.com/NikoHsu/Niko.github.io/master/images/framework.png)](https://www.bilibili.com/video/BV1ri421d7E5)

- **paper2**

- **paper3**
  
Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.

<script type="text/javascript" src="//rf.revolvermaps.com/0/0/6.js?i=54e0ojatafc&amp;m=7&amp;c=e63100&amp;cr1=ffffff&amp;f=arial&amp;l=0&amp;bv=90&amp;lx=-420&amp;ly=420&amp;hi=20&amp;he=7&amp;hc=a8ddff&amp;rs=80" async="async"></script>
