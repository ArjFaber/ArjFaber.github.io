---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* M.S. in Data Science with High Performance Computing, The University of Edinburgh, 2025 (expected).
* B.S. in Econometrics & Operations Research, University of Groningen, 2023.

Work experience
======
* January 2024 - July 2024: ML Research Engineer, University of Twente, Enschede, NL.
  * Duties included: Developed a deep reinforcement learning module for social behavior acquisition of service robots in hospitals. Implemented both inverse reinforcement learning (MaxEnt IRL) and deep reinforcement learning (deep Q-learning). Running a large data collection study, collecting over 3mln data points, and implemented OpenPose deep learning algorithm in ROS Noetic for detecting human body and facial expressions from keypoints on single images and videos. (Used lidar sensor, RealSense cameras and Kinect on a Kuka iDo robot). Implemented 5-Fold CV, introduced metrics such as macro-averaged precision, used oversampling for an imbalanced dataset and adjusted labels based on confidence intervals with a logistic regression model.  

  * Supervisor: Bob Schadenberg, PhD, prof. Gwenn Englebienne. 

* Augustus 2021 - January 2022: Quantitative Modeller Intern, Achmea, Apeldoorn, NL.
  * Duties included: Converted modules for a stochastic model in MATLAB to Python code and implemented option pricing models.
  
  
Skills
======
* Dynamic econometrics, time-series analysis, operations research. 
* Programming:
  * Python , C#, C, C++20 (memory,clang,gtest), MATLAB, R, ReactJS, ROS1/ROS2  and LaTex.  

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Investment Analyst, Senior Investment Team (2019), Financial Study Association Groningen. 
* External Affairs Officer, International Programme Committee (2019), Econometric Study Association Groningen (VESTING).
* Chairman '17-'18, Sports committee, Econometric Study Association Groningen (VESTING).
