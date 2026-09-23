# 6-DOF Robotic Arm - CAD & Simulation

<p align="center">
  <img src="Drawings_Robotic Arm/Image Robotic Arm.png" width="200">
</p>

## Overview

This project focuses on the design and simulation of a **6-DOF robotic manipulator**.

The first stage of the project involved developing a functional mechanical model of the robotic arm in **SolidWorks**, with rigid-body kinematic mates used to define the relative motion between its links and joints.

The CAD model serves as the mechanical foundation for the next stage of the project, which will involve importing the robot into **PyBullet** for trajectory control and reinforcement-learning-based manipulation.

---

## CAD Model

The robotic manipulator was modeled in **SolidWorks** as a multi-link, six-degree-of-freedom mechanism.

The assembly uses rigid-body kinematic mates to constrain the individual mechanical links and represent the motion of the robot's joints.

The CAD model was developed with the intention of maintaining a mechanically consistent representation of the robot that can later be transferred into a physics simulation environment.

### Key features

- 6 degrees of freedom
- Multi-link articulated structure
- Rigid-body mechanical links
- Kinematic joint constraints
- Functional assembly capable of representing robotic motion
- CAD model intended for subsequent physics simulation

---

## Degrees of Freedom

The manipulator is designed as a **6-DOF articulated robotic arm**, allowing the end-effector to achieve both position and orientation control within its workspace.

The six joint variables provide the basis for future:

- Forward kinematics
- Inverse kinematics
- Trajectory generation
- Joint-space control
- End-effector control
- Physics-based simulation

---

## Project Workflow

The intended development pipeline is:

```text
Mechanical Design
       ↓
SolidWorks CAD Model
       ↓
Kinematic Assembly
       ↓
Robot Model Export
       ↓
PyBullet Simulation
       ↓
Trajectory Control
       ↓
Reinforcement Learning
