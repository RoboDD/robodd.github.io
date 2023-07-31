---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

<script src="https://kit.fontawesome.com/0f54bb8f22.js" crossorigin="anonymous"></script>

Towards Human-in-the-loop Robot Learning with Mixed Reality-based Immersive Teleoperation
{: .notice}

<!---
## Roadmap

<img src='/site/images/myresearch.drawio.png' width = "80%" align=center>
--->

## [1] Mixed Reality-based Immersive Teleoperation for Manipulators

[[code]](baidu.com) [[tutorial]](baidu.com) 

Short Abstract: The proposed Mixed Reality (MR) based aims to provide an immersive experience for teleoperation with a master-slave fashion through digital twin and immersive scene. The following Figure A and B indicate the setup and the first-person view of baseline method (i), MR-SC (ii) and MR-PT (iii). The conventional method (Touch) is based on the flat 2D screen and Touch haptic device. The user sits in the front of the display and then uses Touch haptic device to control the position of the end-effector position. The touch device simply adds the incremental position to the current end-effector position. MR-SC refers to the immersive teleoperation with a virtual screen. The user perceives the visual feedback from the 2D embedded virtual screen, while the digital twin (green manipulator) is immersed to provide a sense of being there and the intuitive visual representation of the robot state. Both Touch and MR-SC method has limited field-of-view (FOV) due to the hardware of the RGB camera used. The colored passthrough function with Oculus Pro enables a fully immersive experience so that the user can see all directions of the screen, named as MR-PT. One limitation is that the flat 2D screen and virtual screen are both 2D contents and cannot provide a better sense of depth. The proposed MR-PT method resolves the limitation as the operator interacts with fully immersed contents in 3D to better understand the geometric relation in the real world with a high sense of presence. The user study results shows that MR-PT method is associated with the best performance compared with MR-SC and Touch, including (a) the fastest time of completion, (b) the highest success rate, (c) the lowest levels of user workload, (d) the favorite user experience.
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
  <div style="flex: 1;"><iframe width="140" height="78" src="https://www.youtube.com/embed/36P0c6hg3ZQ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe></div>
  <div style="flex: 1;"><iframe width="140" height="78" src="https://www.youtube.com/embed/a2RNN_HDsXc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>
</div>
</div>


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

TODO

<!---
Imitation Learning and DRL
X=communication, intention, reaction, uncertainty, interaction, privacy, change, energy, context, safety
--->

## [3] Dexterous Contact-Rich Bimanual Manipulation

TODO


Last update: July 31, 2023
