# RRR Articulated Manipulator – Kinematics and Dynamics

This repository contains MATLAB implementations and analysis of a 3-DOF RRR
(Revolute–Revolute–Revolute) articulated spatial manipulator developed as part of the
course **ME 5623 – Mechanics and Control of Robotic Manipulators**.

The project includes forward kinematics, inverse kinematics, Jacobian analysis,
workspace visualization, and dynamic modeling using the Newton–Euler formulation.

---

## Project Overview

The RRR articulated manipulator provides full rotational freedom in 3D space and is
widely used in industrial applications such as welding, painting, and material handling.
This project focuses on:

- Denavit–Hartenberg (DH) parameterization
- Forward and inverse kinematics derivation
- Workspace analysis
- Jacobian and velocity analysis
- Dynamic modeling and joint torque computation
- MATLAB-based animation and trajectory simulation

---

## Features Implemented

### Kinematic Analysis
- Forward kinematics using DH convention
- Closed-form inverse kinematics solution
- End-effector position and orientation computation

### Workspace Analysis
- 3D reachable workspace visualization
- Joint limit–based sampling

### Velocity & Jacobian Analysis
- Analytical Jacobian matrix
- Angular and linear velocity computation

### Dynamic Modeling
- Newton–Euler formulation
- Link-wise angular velocity and acceleration
- Inertial force and moment propagation
- Joint torque expressions

### Simulation & Animation
- Cubic polynomial joint-space trajectories
- Forward kinematics animation
- Inverse kinematics trajectory tracking

---

## Simulation Environment

- MATLAB (R2020a or later recommended)
- Symbolic Math Toolbox (for dynamics derivation)
- Standard 3D plotting functions

---

## How to Run

1. Open MATLAB
2. Navigate to the desired folder
3. Run the main scripts:

```matlab
run_forward_kinematics.m
