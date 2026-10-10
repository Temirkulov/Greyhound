# GREYHOUND Quadruped Robot

A modular quadruped designed in **Autodesk Fusion 360** and built with 3D-printed chassis and leg components. Each leg has three servo-driven joints for hip roll, hip pitch and knee pitch. The system design assigns joint control to an STM32 microcontroller and perception processing to an NVIDIA Jetson Orin Nano.

<img src="IMG_4899.jpg" alt="Assembled quadruped robot" width="720">

## Specifications

| Parameter | Specification |
| --- | --- |
| Configuration | Four legs, three joints per leg |
| Degrees of freedom | 12 |
| Actuation | Position-controlled servo motors |
| Mass | Approximately 5 kg |
| Construction | 3D-printed chassis, leg links and servo mounts |

## Tech stack

| Component | Technology |
| --- | --- |
| Mechanical design | Autodesk Fusion 360 |
| Embedded control | STM32, C, PWM servo control |
| Onboard computing | NVIDIA Jetson Orin Nano |
| Sensing | Intel RealSense D435i RGB-D camera, IMU |
| Robotics software | ROS, CHAMP |
| Computer vision | YOLOv11 |
| Kinematics | MATLAB |
| Physics simulation | MuJoCo |

## Author

**Mirkamol Temirkulov** — BSc (Hons) Computer Science, Sunway University. Designed and built as a university capstone project.
