# GREYHOUND Quadruped Robot

A modular, 12-degree-of-freedom quadruped developed for my Computer Science capstone at **Sunway University**. The project combines mechanical redesign, embedded control, kinematics and simulation, with the long-term goal of indoor autonomous navigation.

<img src="assets/quadruped-prototype.jpg" alt="Assembled quadruped prototype on a supported laboratory test setup" width="720">

## What I built

- Redesigned an inherited robot and assembled the complete four-leg prototype with 3D-printed components.
- Reduced robot mass from approximately **9 kg to 5 kg**, a **44.4% reduction**.
- Checked leg trajectories using MATLAB inverse kinematics and joint limits.
- Demonstrated coordinated single-leg actuation using an STM32 controller.
- Evaluated learned locomotion in MuJoCo; the best shown run achieved **2.12 m of forward displacement in 6 seconds**.
- Demonstrated a YOLOv11 perception prototype on the Jetson.

## Technology

**Mechanical and control:** CAD, 3D printing, servo actuators, STM32, C and MATLAB.

**Simulation and perception:** MuJoCo, NVIDIA Jetson Orin Nano, Intel RealSense D435i, YOLOv11 and ROS/CHAMP.

## Current status

The full mechanical robot is assembled. Kinematics, single-leg control, simulated locomotion and perception were evaluated separately. **Autonomous navigation on the physical robot has not been tested.**

The next steps are to validate full-body gait, integrate sensing and control, and evaluate SLAM, obstacle avoidance and point-to-point navigation.

---

**Author:** Mirkamol Temirkulov · BSc (Hons) Computer Science · Sunway University
