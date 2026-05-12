# STM32 Smart Desktop Pet (Enhanced Version) 

## Overview
This repository contains an open-source, enhanced derivative work of a Smart Desktop Pet. It was developed as the final project for the **Microcomputer Principles and Embedded Systems** course.

The project builds upon an existing open-source desktop pet framework and introduces new hardware interactions and software optimizations, making the pet not just visually interactive, but also spatially aware.

## Features & My Contributions
- **Basic Desktop Pet Functions:** Inherited from the original framework (e.g., animations, basic UI interactions).
- **Autonomous Obstacle Avoidance:** Integrated an ultrasonic sensor (HC-SR04) to measure distances in real-time. The pet can now autonomously detect obstacles in its path and execute avoidance maneuvers.
- **Foreground/Background System Optimization:** Adjusted and optimized the original foreground/background control architecture (interrupt service routines and main loop). This ensures that the real-time processing of ultrasonic sensor data and motor control does not block or interfere with the smooth rendering of the UI animations.

## Acknowledgments & Credits
The basic software framework and UI design of this project are based on the fantastic open-source work by **sngelswyh**:
👉 [Original Project Link on OSHWHub](https://oshwhub.com/sngelswyh/stm32-smart-desktop-pet)

Special thanks to the original author. My main contributions lie in the integration of the ultrasonic autonomous obstacle avoidance system and the restructuring of the foreground/background control logic.
