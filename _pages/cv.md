---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download Chinese CV PDF](/xzs_cv_cn.pdf)

## Education

- **Beijing Institute of Technology**, B.S. and M.S. in Control Science and Engineering. M.S. expected June 2027.

## Research Experience

- **Research Assistant**, School of Computer Science, Peking University, Prof. Hao Tang's Lab. Oct 2025 - Present.  
  Working on world-model-based embodied policies for mobile robot navigation, including action-conditioned prediction, rollout consistency, inference acceleration, and robot deployment.

## Selected Industry Experience

- **Embodied Intelligence Algorithm Intern**, Fifth Era Intelligent Technology. Jun 2025 - Sep 2025.  
  Worked on vision-language-action algorithms for dual-arm mobile robot platforms, including LeRobot-based reproduction, training, inference systems, and embodied application demos.

## Selected Projects

- **MWM: Mobile World Models for Action-Conditioned Consistent Prediction**.  
  [Paper](https://arxiv.org/abs/2603.07799) / [Project Page](https://aigeeksgroup.github.io/MWM) / [Code](https://github.com/AIGeeksGroup/MWM)

- **ROS2-based three-wheel omnidirectional mobile robot**.  
  Built and integrated sensing, mapping, planning, and navigation modules with LiDAR, RGB-D camera, IMU, GPS, Cartographer, RTAB-Map, A* planning, DWB local planning, and MPC control.

## Skills

- Programming and tools: Python, MATLAB/Simulink, ROS2
- Robotics: trajectory planning, trajectory optimization, imitation learning, CoppeliaSim, MuJoCo
- Embodied learning: ACT, Diffusion Policy, PI-series methods, VLA systems

## Publications

<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
