---
layout: archive
title: "My Research"
permalink: /research/
author_profile: true
---



## Autonomous Docking for Unmanned Surface Vehicles (USV)

- Remote control by human operators is often required to complete the re-docking of the USV to the docking station after the operations;
- It is a challenge for the unmanned deployment of fully autonomous USVs. Therefore, we address the last-mile problem: autonomous docking;
- More details are coming soon!

<div style="display: flex;">
  <div style="flex: 1;"><img src='/images/usv-docking.gif' width = "100%" align=center></div>
  <div style="flex: 1;"><img src='/images/usv-dock-real-web.png' width = "100%" align=center></div>
</div>

## Mixed Reality-based Fully Immersive Teleoperation for Robotic Manipulation (MSc Dissertation, Internship)

- Developed a fully immersive teleoperation framework (MR-PT) for teleoperation using ROS, Unity and Quest Pro;
- Conducted user studies to quantitatively demonstrate that MR-PT outperforms the benchmark methods;
- Performed extensive real-world experiments using the Kinova Gen 3 robot and MyCobot 320 arm;
- Implemented quadratic programming for motion control (QPMC) in both Isaac Sim and Kinova Gen 3.

<div style="display: flex;">
  <div style="flex: 1;"><iframe width="560" height="315" src="https://www.youtube.com/embed/D_Ta6EO0uyI" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe></div>
  <div style="flex: 1;"><iframe width="140" height="78" src="https://www.youtube.com/embed/mRZG9t2mmKE" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe></div>
</div>


- Awarded the [Most Accomplished Project]() award at the Robot Demo Day from the University of Bristol;
- Contributed to [HuBotVerse project](https://sites.google.com/view/iohirtplusmr/home) as a core team member which led to the acceptance of a publication in IEEE Robotics and Automation Magazine (RA-M).

## Optimization-based Motion Planning Algorithms for Quadrotors (BSc Final Year Project)

- Systematically reviewed the motion planning methods, including graph search, sampling-based, optimization-based;
- Implemented path search on a grid map using A* and back-end optimization to generate minimum-snap trajectory;
- Conducted high-fidelity simulations using AirSim, Python and Matlab to quantitatively evaluate the performance;


## Motion Planning and Control for Unmanned Surface Vehicles

- Implemented an improved artificial potential field (APF) method for USV obstacle avoidance using Python and ROS;
- Developed a river bank following local planner based on the point clouds, and validated in Gazebo simulator (VRX);
- Analyzed, evaluated and discussed experimental data involving MATLAB and Python (seaborn, etc.)


## Development of Micro Aerial Vehicle for On-site Water Sampling (SURF)



Abstract: On-site water sampling is essential for water environment monitoring and management. We developed an autonomous micro aerial vehicle (MAV) to help users to collect water samples in complicated water environments. We designed the airframe and sampler mechanics, assembled and configured the system with additional onboard sensors, suc has GPS, sonar, monocular and depth cameras. Furthermore, several advanced features for autonomous navigation are achieved, such as takeoff, hovering, landing, collision avoidance, auto water sampling and return-to-launch (RTL). Experimental results show that our MAV is robust, easy-to-use in outdoor, and can significantly improve work efficiency.

Hardware:

<img src='/images/surf21-system.png' width = "70%" align=center>

Onsite Experiments:

<img src="/images/surf21-experiment.png"/>


Demo:

<iframe width="560" height="315" src="//player.bilibili.com/player.html?aid=290079202&bvid=BV1Af4y1s74f&cid=324630542&page=1" scrolling="no" border="0" frameborder="no" framespacing="0" allowfullscreen="true"> </iframe>

My Contributions: 
- Developed and tested a micro aerial vehicle to collect water samples in complicated on-site water environments;
- Designed and manufactured the foldable airframe structure and modular sampler structure using SolidWorks;
- Assembled and configured the quadrotor with PX4 Autopilot and peripherals, including GPS, telemetry, etc;
- Developed a PX4 module based on Nuttx to remotely control water sampler using uORB and MAVLink;
- Implemented a position-based vision servoing for the precise landing in ROS using OpenCV and ArUco markers.

Last update: April 9, 2024
