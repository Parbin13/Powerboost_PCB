# PCB Power Booster and Controller

This repository contains the design files for a custom PCB created to boost 5V power to 12V and control various components such as solenoids, servos, and ultrasonic sensors. The PCB was designed using KiCAD and includes schematic and layout files, as well as 3D renderings of the final board.

## Project Overview
This PCB is designed for a project that involves controlling components while boosting a 5V input power supply to 12V for powering solenoids and other devices. It includes the following features:
- **Boost Converter**: Steps up 5V to 12V for high-power components.
- **Solenoid Driver**: Controls solenoids using the boosted 12V power.
- **Ultrasonic Sensor Interface**: Allows connection and control of ultrasonic sensors.
- **Servo Motor Controllers**: Provides control for multiple servos.

The PCB was designed using KiCAD, an open-source electronic design automation (EDA) tool.

### PCB Features
- **Power Boost Circuit**: Converts 5V input to 12V using a boost converter, providing sufficient power for solenoids and other high-power components.
- **Microcontroller Interface**: Designed to work with a microcontroller for controlling external components.
- **Component Footprints**: Includes headers for connecting solenoids, ultrasonic sensors, and servos.
- **Power Supply and Regulation**: Manages power distribution and voltage regulation for all components.

## Project Files
- **Schematic File (.sch)**: Contains the electronic circuit schematic, including the boost converter and control components.
- **Layout File (.kicad_pcb)**: Contains the PCB layout, routing, and component placement.
- **3D Model**: Visual representation of the PCB design to assist in assembly.

## Setup Instructions
To view and modify the PCB design:
1. Install **KiCAD** from [here](https://kicad.org/).
2. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/PCB_PowerBooster_Controller.git
