# aquashell
 A multi-mode underwater robot featuring a custom-designed shell and an assembly of open-source components. This project combines remote-controlled and autonomous operation, integrating advanced sensors (pressure, temperature, gyroscope), a camera, and automated buoyancy adjustment for stable underwater navigation. Powered by Raspberry Pi 4 and Arduino UNO, the robot utilizes ROS for multi-node task management and LiFi communication for reliable data transfer underwater. Designed with ABS for robust, watertight construction, the system is suitable for marine research, inspection, environmental monitoring, and educational applications. The shell is original work; other mechanical components are sourced from GrabCAD

## Overview

UWR is a submarine-style underwater robot designed for both remote-controlled and autonomous operation. The project features a custom 3D-modelled shell (original work) and an assembly of open-source components, integrating advanced sensors, a camera, and automated buoyancy control for stable underwater navigation.

---
![image](https://github.com/user-attachments/assets/a073c23d-44c6-49d4-87e3-897aa0eb13fe)


## Repository Structure

- **submarine assembly/**  
  Main assembly files for the UWR robot (custom shell, GrabCAD components).
- **/old_try/**  
  Early prototypes and design attempts.

---

## Technical Specifications

- **Dimensions:** 500 mm (L) × 350 mm (W) × 104 mm (H)
- **Processing Units:** Raspberry Pi 4, Arduino UNO
- **Power Supply:** 12V 10,000 mAh (2 batteries in parallel)
- **Material:** ABS (3D-printed for strength and water resistance)
- **Software:** ROS (Robot Operating System), multi-node configuration

---

## Key Features

- Pressure, temperature, and depth sensors
- Automated buoyancy adjustment for stable positioning
- Manual and autonomous operation modes
- Real-time video feedback via camera module (OV5647)
- Robust mechanical structure with thrusters and actuators
- LiFi Nano-V2 module for underwater communication

---

## Methodology

1. Concept design and 3D modeling
2. Electronic circuit design (EasyEDA)
3. Component selection and procurement
4. Circuit assembly and programming
5. Mechanical assembly and optimization
6. Logic testing and integration

---

## Motion and Buoyancy Control

- **Forward/Backward:** Propeller rotation direction
- **Turning:** Differential propeller speeds
- **Buoyancy:** Linear actuators adjust syringes for fluid control
- **Stability:** Gyroscope for orientation; pressure sensor for depth

---

## Main Components

- **Shell:** Custom-designed (original)
- **Other parts:** Sourced from GrabCAD
- **Sensors:** Pressure, temperature, gyroscope, camera
- **Actuators:** BLDC motors, linear actuators
- **Communication:** LiFi for underwater data transfer

---

## Applications

- Marine research and data collection
- Underwater inspection and maintenance
- Military and defense (e.g., mine inspection)
- Archaeology (site exploration and mapping)
- Environmental monitoring (water quality, pollution)
- Fishing industry (locating fish shoals)

---

## Acknowledgments

- Shell design: Adithya Pothula
- Other components: Sourced from GrabCAD

---
