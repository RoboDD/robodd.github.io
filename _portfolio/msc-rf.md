---
title: "Serial and Parallel Robot Modeling and Analysis"
excerpt: "MSc Group Project - EMATM0058 Robotic Fundamentals"
collection: portfolio
---


Group Project:
======

Abstract
This report is the coursework for Robotic Fundamentals and is divided into three
main sections: Lynxmotion Arm, Planar Parallel Robots and Optimisation-based
Trajectory Generation.
In Section 1, we first define a forward kinematic model of the five-degree-of-freedom
Lynxmotion Arm by Modified DH representation and analyse the reachable workspace
of its wrist. We then generate an inverse kinematic model of the Lynxmotion Arm
by geometric method. Finally, we apply the obtained forward and inverse kinematic
models to plan three trajectories between five positions (free motion, straight line and
obstacle avoidance).
In Section 2, we first derive the inverse kinematic model of the planar parallel robot,
which is similar to the delta robot, by the vector method. We then use the algebraic
method to solve the expression for its workspace and the root formula for the quadratic
function to determine whether it is a real solution.
Inspired by the trajectory planning in Section 1, we introduce in Section 3 a minimumsnap
trajectory generation scheme for robot arm in the geometric space that allows
the selection of the optimal coefficients of the polynomial as a quadratic planning
problem. A numerical example is given to validate the method in one dimension.
It ends with a conclusion and references. Almost all the codes in the paper can be
found in appendices.

[Download our group report](https://github.com/RoboDD/site/raw/master/files/RF-Report.pdf)
