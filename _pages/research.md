---
layout: archive
title: "MSc Dissertation Project"
permalink: /research/
author_profile: true
---

<script src="https://kit.fontawesome.com/0f54bb8f22.js" crossorigin="anonymous"></script>

Towards Human-in-the-loop Robot Learning with Mixed Reality-based Immersive Teleoperation, supervised by: Dr. Dandan Zhang
{: .notice}

<!---
## Roadmap

<img src='/site/images/myresearch.drawio.png' width = "80%" align=center>
--->

## [1] Mixed Reality-based Fully Immersive Teleoperation for Manipulators



Abstract: The proposed systems aim to provide a **fully immersive** experience for intuitive teleoperation in a master-slave fashion. The following Figure A and B indicate the setup and the first-person view of baseline method (i), MR-SC (ii) and MR-PT (iii). The conventional method (Touch) is based on the flat 2D screen and Touch haptic device. The user sits in the front of the display and then uses Touch haptic device to control the position of the end-effector position. The touch device simply adds the incremental position to the current end-effector position. MR-SC refers to the immersive teleoperation with a **virtual screen**. The user perceives the visual feedback from the 2D embedded virtual screen, while the digital twin (green manipulator) is immersed to provide a sense of being there (embodiment) and the intuitive visual representation of the robot state (situation awareness). Both Touch and MR-SC method has limited field-of-view (FOV) due to the hardware of the RGB camera used. The **colored passthrough** function with Oculus Pro enables a fully immersive experience so that the user can see all directions of the screen, named as MR-PT. One limitation is that the flat 2D screen and virtual screen are both 2D contents and cannot provide a better **sense of depth**. The proposed MR-PT method resolves the limitation as the operator interacts with fully immersed contents in 3D to better understand the geometric relation in the real world with a high sense of presence. The system architecture is shown in Figure C, which is integrated with ROS to support various robot platforms. 8 participants were invited to do a user study by pick-and-place cubes into the colored bins (Figure D). The user study results show that MR-PT method is associated with the best performance compared with MR-SC and Touch, including (a) the fastest time of completion, (b) the highest success rate, (c) the lowest levels of user workload, (d) the favorite user experience. MR-PT method may enable users to do learning demonstrations in a large and continuous workspace with the combination of human-machine hybrid intelligence, which provides a good start for robot learning. Bidirectional haptic rendering will be developed soon.
{: .notice}


<img src='/site/images/teleoperation-system.png' width = "100%" align=center>

<!---
Features:

- Immersive and intuitive direct control in the master-slave fashion
- Fully ROS based for modularized development
- Fundamental tools for collecting robot training data by human demonstration

Demo for pick-and-place:
--->

<div style="display: flex;">
  <div style="flex: 1;"><iframe width="140" height="78" src="https://www.youtube.com/embed/TZ5NerQ3owE?si=UbURkiZqYUwRExoD" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe></div>
  <div style="flex: 1;"><iframe width="140" height="78" src="https://www.youtube.com/embed/Yh0GjJybq-Q?si=-Yt3ECp5lu3AfzMd" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe></div>
  <div style="flex: 1;"><iframe width="140" height="78" src="https://www.youtube.com/embed/dybKVHivjg8?si=im08uNfXpo_KTnOk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>
</div>

User study results, code, and tutorial will release soon.

[[code]](baidu.com) [[tutorial]](baidu.com) 

This work received the [Most Accomplished Project]() award at the [Robot Demo Day](), hosted by the University of Bristol.

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

## [2] Human-in-the-loop Imitation Learning

TO BE UPDATE

Why do we need human-in-the-loop? In order to improve the robot learning efficiency, we assume human-in-the-loop learning demonstrations can be considered a good initial solution for complex manipulation tasks. Mathematical optimization, imitation learning, as well as reinforcement learning, requires good initial guess to start. The model may converge to better performance as we have a good initial guess with the combination of human-machine hybrid intelligence. More details will be updated soon.
{: .notice}

Reproduced Coarse to fine imitation learning:

<iframe width="560" height="315" src="https://www.youtube.com/embed/lMMjPFS0FJk?si=EKCJnKKJk1JP5jkI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

Reference: E. Johns, Coarse-to-Fine Imitation Learning: Robot Manipulation from a Single Demonstration, arXiv:2105.06411 [cs], Jun. 2021. DOI: 10 . 48550 / arXiv . 2105 . 06411. available from: http://arxiv.org/abs/2105.06411 [Accessed 08/28/2023].


Future work:

<img src='/site/images/algo_overview.png' width = "100%" align=center>

Image Source: [link](https://robomimic.github.io/study/)


<!---
Imitation Learning and DRL
X=communication, intention, reaction, uncertainty, interaction, privacy, change, energy, context, safety
--->


<!---
## [3] Dexterous Contact-Rich Bimanual Manipulation

TODO
--->

Last update: Sep. 1, 2023
