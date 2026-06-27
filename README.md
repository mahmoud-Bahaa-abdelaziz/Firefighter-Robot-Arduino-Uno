# Firefighter-Robot-Arduino-Uno
Developed an autonomous firefighter robot using Arduino Uno and Embedded C. Implemented line following with IR sensors, obstacle avoidance using an ultrasonic sensor with servo scanning, and flame detection with autonomous emergency response. Integrated real-time motor control and sensor-based navigation
# Firefighter Robot using Arduino Uno

## Overview

This project is an autonomous firefighter robot built using an Arduino Uno. The robot follows a predefined path, detects and avoids obstacles, and identifies fire using flame sensors. When a flame is detected, the robot stops, retreats to a safe distance, and activates an LED alarm to indicate the presence of fire.

## Features

* Autonomous line following using two IR sensors.
* Obstacle detection with an HC-SR04 ultrasonic sensor.
* Servo-based ultrasonic scanning to determine the safest path around obstacles.
* Flame detection using dual flame sensors.
* Automatic emergency response when fire is detected.
* Real-time motor control for forward, backward, left, and right movement.

## Hardware Components

* Arduino Uno
* HC-SR04 Ultrasonic Sensor
* Servo Motor
* 2 × IR Line Tracking Sensors
* 2 × Flame Sensors
* L298N Motor Driver
* DC Motors
* LED Indicator
* Robot Chassis and Battery Pack

## Software

* Arduino IDE
* Embedded C
* Servo Library

## System Workflow

1. The robot follows a line using the IR sensors.
2. The ultrasonic sensor continuously measures the distance to obstacles.
3. If an obstacle is detected, the servo rotates the ultrasonic sensor to scan both directions.
4. The robot compares the left and right distances and selects the safest path.
5. Flame sensors continuously monitor for fire.
6. When a flame is detected, the robot:

   * Stops immediately.
   * Moves backward to a safe distance.
   * Activates an LED indicator.
   * Waits until the fire is no longer detected.

## Technologies Used

* Arduino Uno
* Embedded C
* Servo Motor Control
* Ultrasonic Distance Measurement
* Sensor Integration
* Motor Control
* Robotics
* Real-Time Embedded Systems

## Future Improvements

* Add a water pump or fan for automatic fire extinguishing.
* Integrate Bluetooth or Wi-Fi for remote monitoring.
* Implement computer vision using a Raspberry Pi.
* Improve navigation with PID control.
* Add GPS and IoT support for outdoor applications.

## Author

Mahmoud Bahaa
