![image](https://github.com/RoboDD/robodd.github.io/assets/48425290/dd775e3b-b506-4b33-8f09-a395807f9615)---
layout: archive
title: "My Research"
permalink: /research/
author_profile: true
---

<script src="https://kit.fontawesome.com/0f54bb8f22.js" crossorigin="anonymous"></script>

<!--
| Cate | Topic           | Supervisor                         | 
|------|----------------|------------------------------|
| MSc Dissertation   | Mixed Reality-based Fully Immersive Teleoperation for Human-in-the-loop Robot Learning | Dr. Dandan Zhang               |
| BSc Final Year Project   | Optimization-based Motion Planning Algorithms for Quadrotors | Dr. Ruonan Zhang | 
-->

## Autonomous Docking for Unmanned Surface Vehicles (USV)

- Remote control by human operators is often required to complete the re-docking of the USV to the docking station after the operations;
- It is a challenge for the unmanned deployment of fully autonomous USVs. Therefore, we address the last-mile problem: autonomous docking.

<img src='/images/usv-dock.png' width = "100%" align=center>

## Mixed Reality-based Fully Immersive Teleoperation for Robotic Manipulation

MSc Dissertation Project  
Supervisor: [Dr. Dandan Zhang](https://www.intelligentrobotics-acrossscales.com/about)  







<!---
Features:

- Immersive and intuitive direct control in the master-slave fashion
- Fully ROS based for modularized development
- Fundamental tools for collecting robot training data by human demonstration

Demo for pick-and-place:
--->


<!---
<div style="display: flex;">
  <div style="flex: 1;"><iframe width="140" height="78" src="https://www.youtube.com/embed/TZ5NerQ3owE?si=UbURkiZqYUwRExoD" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe></div>
  <div style="flex: 1;"><iframe width="140" height="78" src="https://www.youtube.com/embed/Yh0GjJybq-Q?si=-Yt3ECp5lu3AfzMd" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe></div>
  <div style="flex: 1;"><iframe width="140" height="78" src="https://www.youtube.com/embed/a2RNN_HDsXc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>
</div>
--->


<div style="display: flex;">
  <div style="flex: 1;"><iframe width="560" height="315" src="https://www.youtube.com/embed/D_Ta6EO0uyI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe></div>
  <div style="flex: 1;"><iframe width="140" height="78" src="https://www.youtube.com/embed/mRZG9t2mmKE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe></div>
</div>


<!---
User study results, code, and tutorial will release soon.
--->


---

<!---
Limitation:

- The degree of freedom of the "wrist" is reduced, 7-DoF arm will be used later.


<i class="fa-regular fa-calendar-check"></i> Next:
- ~~safety consideration design~~ by adding joint limits through finalIK
- ~~Mixed reality-based teleoperation~~
- ~~adopt to cloud computing framework~~ adopted to IoRT framework
- Implementation with Kinova Arm
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

--->

<!---
## [2] Human-in-the-loop Imitation Learning
--->

<!---
TO BE UPDATE

Why do we need human-in-the-loop? In order to improve the robot learning efficiency, we assume human-in-the-loop learning demonstrations can be considered a good initial solution for complex manipulation tasks. Mathematical optimization, imitation learning, as well as reinforcement learning, requires good initial guess to start. The model may converge to better performance as we have a good initial guess with the combination of human-machine hybrid intelligence. More details will be updated soon.
{: .notice}
--->

<!---
### Demo of Coarse-to-Fine Imitation Learning

<iframe width="560" height="315" src="https://www.youtube.com/embed/lMMjPFS0FJk?si=EKCJnKKJk1JP5jkI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

This work received the [Most Accomplished Project]() award at the [Robot Demo Day](), hosted by the University of Bristol.
--->

## Bimanual Robotics Manipulation

Developed a Mixed Reality based teleoperation software with advanced motion controller (resovled-rate controller) and QPMC.

<iframe width="560" height="315" src="https://www.youtube.com/embed/0qPM01FiiFY" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

Preview video. Not the final version.

## Continual Learning for Dynamical Systems
TODO


Last update: Jan. 30, 2024
