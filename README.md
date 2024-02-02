# Smart Car Project

## Overview

This project involves building a Smart Car with various components that allow it to navigate autonomously and respond to environmental stimuli. The car incorporates features such as line following, obstacle detection and avoidance, and ambient temperature control.

## Required Components

- Arduino Uno R3 SMD
- DC Motor
- Gear Motor
- Servo Motor
- Stepper Motor Driver
- Sonar Sensor (HC-SR04)
- LM35 Temperature Sensor
- Digital IR Sensor
- Switch
- LED Light
- Fan
- Jumper Wires
- 9 Volt Battery

## Working Procedure

The Smart Car operates using the following key components:

### Components Reacting to Input

- Gear Motor
- Servo Motor
- DC Motor
- LED Light

### Components Interacting with the Environment

- LM35 Temperature Sensor
- HC-SR04 Sonar Sensor
- IR Obstacle Sensor

## Features

The Smart Car is designed to exhibit the following features:

1. **Line Following:**
   - The car can drive automatically, following lines with the help of IR obstacle sensors.

2. **Obstacle Detection and Avoidance:**
   - When an obstacle is detected in front of the car, it will come to a stop and analyze the route.
   - The car will identify an obstacle-free route using the sonar sensor and continue its journey.

3. **Smart Ambient Control:**
   - The car features a smart ambient control system that regulates its temperature.
   - The fan's speed adjusts based on the ambient temperature, measured by the LM35 temperature sensor.

## Setup and Usage

1. Connect the specified components as per the provided circuit diagram.
2. Upload the Arduino code to the Arduino Uno.
3. Power the Smart Car using the 9 Volt Battery.
4. Observe and test the different features of the Smart Car.

Feel free to explore and modify the Arduino code to enhance or customize the behavior of your Smart Car.

Happy tinkering!
