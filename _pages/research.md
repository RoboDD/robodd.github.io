---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

This page is updateing!!!!!!
This page is updateing!!!!!!
This page is updateing!!!!!!

<html>
    <table style="margin-left: auto; margin-right: auto; border: none">
        <tr style="border: none">
            <td style="border: none">
                <div align="center" id="member">
                <img src="/site/images/mm-realsense-test.png" width="300px">
                </div>
            </td>
            <td style="border: none">
                <div align="left" id="member">
                <p>
                <b>Mixed Reality for Contact-Rich Manipulation with Mobile Manipulator</b><br>
                Description: To improve the performance of mobile manipulation in an unstructured environment, the aim of this research is to develop a human-in-the-loop teleoperation method with human-robot hybrid intelligence that enables mobile manipulators to collaborate with human operators with shared autonomy and high situational awareness while reducing the human supervisory workload. 
                </p>
                </div>
            </td>
        </tr>
        <tr style="border: none">
            <td style="border: none">
                <div align="center" id="member">
                <img src="/site/images/mm-unity-demo.png" width="300px">
                </div>
            </td>
            <td style="border: none">
                <div align="left" id="member">
                <p>
                <b>Human-in-the-loop Planning for Robots</b><br>
                Description: To improve the performance of mobile manipulation in an unstructured environment, the aim of this research is to develop a human-in-the-loop teleoperation method with human-robot hybrid intelligence that enables mobile manipulators to collaborate with human operators with shared autonomy and high situational awareness while reducing the human supervisory workload. 
                </p>
                </div>
            </td>
        </tr>
    </table>
</html>


## Mixed Reality for Contact-Rich Manipulation with Mobile Manipulator

Supervisor: [Dr. Dandan Zhang](https://www.intelligentrobotics-acrossscales.com/) and [Prof. Nathan Lepora](https://lepora.com/)

Working on it!

## Progress

* High-fidelity Simulator (Digital twin)
  * Support Leo Rover and WX250 robot manipulator
  * ROS Connection
  * 2D LiDAR
* VR-based teleoperation client
  * Publish \cmd_vel by VR joystick control through ROS
* Algorithm:
  * Navigation: GMapping+AMCL+Navigation stack(A*+TEB)
  * Manipulation: TODO
* Teleoperation:
  * PCD display in headset+EFF controller
  * Objective-based Shared Controller

## Screenshots
<img src='/site/images/mm-unity-demo.png' width = "50%" align=center>

<img src='/site/images/mm-vr-test.jpg' width = "50%" align=center>

<img src='/site/images/mm-realsense-test.png' width = "50%" align=center>

<img src='/site/images/mm-lidar-test.png' width = "50%" align=center>

Last update: Feb. 28, 2023
