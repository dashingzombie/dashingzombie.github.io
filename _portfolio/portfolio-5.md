---
title: "Robot-Assisted Sensor Calibration"
excerpt: "An automated ROS, Gazebo, and UR5 extrinsic-calibration pipeline validated through sub-2 mm 3D reconstruction residuals."
collection: portfolio
---

## Challenge

Low-cost time-of-flight sensors are useful only when their pose relative to the system is known accurately. Manual calibration is slow and difficult to validate consistently.

## System

I developed an automated extrinsic-calibration workflow for VL53L3CX and VL6180X sensors using ROS, Gazebo, and a UR5 arm.

## Result

The workflow achieved positional accuracy of **3.18 mm and 7.29 mm** and orientation accuracy of **0.61° and 2.01°** across the two sensor models. End-to-end pose validation through 3D reconstruction produced residual errors below **2 mm** on unseen planar targets.

[Read the IEEE RA-L paper](https://doi.org/10.1109/LRA.2022.3176453)
