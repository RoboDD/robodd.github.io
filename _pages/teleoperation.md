---
layout: archive
title: "Towards Human-in-the-loop Robot Learning with Mixed Reality-based Immersive Teleoperation"
permalink: /teleoperation/
author_profile: true
---

<script src="https://kit.fontawesome.com/0f54bb8f22.js" crossorigin="anonymous"></script>

<iframe src="//player.bilibili.com/player.html?aid=616420800&bvid=BV1Rh4y1V7KA&cid=1211646332&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>

## Roadmap

<img src='/site/images/myresearch.drawio.png' width = "100%" align=center>

## Project I: Virtual Reality and Mixed Reality based Teleoperation for Robot Arm

Features:

- Immersive and intuitive direct control in the master-slave fashion
- Fully ROS based for modularized development
- Fundamental tools for collecting robot training data without Sim2Real gap

Short demo for tidy-up task:

<iframe width="560" height="315" src="https://www.youtube.com/embed/36P0c6hg3ZQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>


<iframe width="560" height="315" src="https://www.youtube.com/embed/a2RNN_HDsXc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

Limitation:

- The degree of freedom of the "wrist" is reduced, 7-DoF arm will be used later.


<i class="fa-regular fa-calendar-check"></i> Next:
- ~~safety consideration design~~ by adding joint limits through finalIK
- ~~Mixed reality-based teleoperation~~
- ~~adopt to cloud computing framework~~ adopted to IoRT framework (will release soon)!
- switch to 'Articulation' version, IK required
- enhance user experience (Jitter removal, trajectory smooth)
- trajectories optimization using Gaussian Process Regression (GPR)
- add point cloud rendering, and extra modules (Point Clouds Completion)
- Gaze track and rough approach
- Gimbal camera (mount camera on 6DOF mycobot to provide immersive view)?
- Digital twin feedback?
- a user-friendly IK solver? (no strange pose)
- add 6 DOF object detection?
- add tactile feedback?
- Integrate with mobile manipulator: improve mobility
- uses URP instead of the default render pipeline for better graphical performance?


## Project II: X-aware Shared Control (Human-in-the-loop)

X=communication, intention, reaction, uncertainty, interaction, privacy, change, energy, context, safety

## Project III: Robot Learning: Imitation Learning and DRL

## Project IV: Dexterous Contact-Rich Bimanual Manipulation




Last update: Junn 30, 2023
