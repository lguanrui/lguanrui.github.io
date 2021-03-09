---
title: "PCMPC: Perception-Constrained Model Predictive Control for Quadrotors with Suspended Loads using a Single Camera and IMU"
<!--collection: publications-->
permalink: /publications/PCMPC2021ICRA
---

<b>Authors: </b> Guanrui Li\*, Alex Tunchez\*, Giuseppe Loianno

![2021icra](https://lguanrui.github.io/images/pcmpc2021icra.jpg)

## Abstract
In this paper, we address the Perception-Constrained Model Predictive Control (PCMPC) and state estimation problems for quadrotors with cable suspended payloads using a single camera and Inertial Measurement Unit (IMU). We design a receding--horizon control strategy for cable suspended payloads directly formulated on the system manifold configuration space \text{$SE(3)\times S^2$}. The approach concurrently takes into account the system dynamics, actuator limits and the camera's Field Of View (FOV) constraint to guarantee the payload's visibility during motion. The monocular camera, IMU, and vehicle's motor speeds are jointly combined to provide an estimate of states of the vehicle in 3D space as well as the payload's state and the cable direction and velocity. The proposed control and state estimation solution runs in real-time at 500 Hz on a small quadrotor equipped with a limited computational unit. The approach is validated through experimental results considering a cable suspended payload trajectory tracking problem at different speeds.

