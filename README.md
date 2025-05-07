# robotic-arm-5DoF
A 5DoF robotic arm built from scratch as part of my Computer Engineering final project (TCC). This repository documents the entire development process, including design, electronics, mechanics, firmware, and testing.

## Objectives

- Design and 3D print the mechanical structure of the robotic arm.
- Implement kinematic and dynamic control (PID, LQR, MPC) for precise motion.
- Use a camera and computer vision (OpenCV) for object recognition.
- Integrate the full system into a simulated environment (Gazebo).
- Perform all tasks autonomously using a Raspberry Pi.

## Components

- **4x NEMA 17 stepper motors**
- **1x MG996R servo motor** (gripper)
- **Drivers:** TB6600 and TMC2209
- **24V power supply**
- **Buck converter** (step down)
- **Raspberry Pi** (control and processing)
- **Logitech C920 USB Camera**
- **3D-printed structure (PLA)**

## Technologies and Tools

- **SolidWorks** – 3D modeling
- **Ultimaker Cura** – 3D printing preparation
- **KiCAD** – Circuit and PCB design
- **OpenCV** – Computer vision
- **C++ + Qt** – Desktop interface
- **Gazebo** – Robotic simulation

## Modeling and Control

- Direct and inverse kinematics using Denavit-Hartenberg parameters
- PID, LQR, and MPC control strategies
- Path planning based on visual input

## Computer Vision

- Color and contour-based object segmentation
- Estimation of object position and orientation
- Integration with control system for autonomous decision-making

## Project Structure
