---
title: "PID and LQR Control for Line Following: Performance Evaluation and Analysis"
excerpt: "MSc Course Project - EMATM0054 Robotic Systems"
collection: portfolio
---

Part 1: Line following challenge
======

<iframe width="560" height="315" src="https://www.youtube.com/embed/ppUrGDie5EU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


Part 2 Group Project: PID and LQR Heading Controller for Line Following: Performance Evaluation and Analysis
======

Abstract: The aim of this report is to evaluate the performance of PID and LQR control methods for robot heading control in line following challenge. The full and comprehensive code for these two algorithms is implemented on the nonholonomic differential drive robot and the 3Pi+ robot is tested in the different settings of parameters and maps. This report finally presents the results of our experiments and compares the performance and discusses the performance of controllers and analysis of errors. The LQR-based method performs stable behavior rather than PID.

[Report]()

[Code for 3Pi+ robot](https://github.com/RoboDD/Differential-Drive-Line-Following)

Version description:
* V1.0: Achieved very simple line following
    * motor driver
    * line sensors driver
    * Bang-bang controller
    * Straight line
* V2.0: Achieved improved line following
    * 90 degree cornor
    * 135 degree cornor
    * Finite-state-machine (FSM)
    * utility driver: beep and led
    * auto map selection
* V3.0: Achieved line following challenge, eared 95% marks for assessment 1 [[video]](https://www.youtube.com/watch?v=ppUrGDie5EU&ab_channel=RoboDDai)
    * encoder driver
    * join the line at 90 degree
    * simple odometry (by count)
    * simple return-to-home (RTH)
* v4.0: Achieved comprehensive line following, baseline for group report
    * wheel speed estimation using encoder
    * low pass filter
    * task scheduler: multi-tasking programming for Arduino
    * full PID
    * cascaded control architecture
        * Heading Controller (PID)->Motor Speed Controller (PID)
    * refact all code
* v5.0: LQR-based heading controller
    * odometry (x,y, theta)
    * data recoder


