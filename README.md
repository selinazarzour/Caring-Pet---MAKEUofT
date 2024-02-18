# Caring Pet Vehicle Control using MPU6050

This project implements a caring pet vehicle controlled by an MPU6050 sensor, designed to detect tilts in a user's hand and respond accordingly. The vehicle moves forward or backward based on the tilt angle detected by the MPU6050 sensor.

## Overview

The code presented here utilizes the MPU6050 sensor's DMP (Digital Motion Processor) functionality to capture orientation data and control the movement of a caring pet vehicle. The vehicle's movement is governed by the tilt of the user's hand, which is detected by the MPU6050 sensor attached to the hand.

## Hardware Requirements

- Arduino board (e.g., Arduino Uno)
- MPU6050 sensor
- Motor driver (compatible with the chosen motors)
- Motors (to drive the vehicle)
- Power source (e.g., batteries)

## Software Requirements

- Arduino IDE
- MPU6050 library (included in the code)

## Installation and Setup

1. **Install Libraries**: Ensure that the MPU6050 library is installed in your Arduino IDE.

2. **Hardware Setup**: Connect the MPU6050 sensor and the motor driver to the Arduino board following the pin configurations defined in the code. Make sure all connections are secure.

3. **Upload Code**: Copy the provided code into your Arduino IDE and upload it to your Arduino board.

4. **Calibration**: After uploading the code, the MPU6050 sensor requires calibration to ensure accurate readings. Follow the calibration procedure outlined in the code comments.

5. **Power On**: Power on the Arduino board and the caring pet vehicle.

## Operation

- Once the system is powered on, the caring pet vehicle waits for initialization and calibration to complete.
- The MPU6050 sensor continuously monitors the orientation of the user's hand.
- Based on the tilt angle detected by the sensor:
  - If the hand is tilted forward, the caring pet vehicle moves forward.
  - If the hand is tilted backward, the caring pet vehicle moves backward.
  - If the hand remains level, the caring pet vehicle stops.

## Additional Notes

- Ensure that the motor driver and motors are properly configured and connected to the Arduino board.
- Adjust motor speed and tilt angle thresholds as needed to optimize the performance of the caring pet vehicle.
- Regularly check and maintain the hardware components for optimal functionality.

## License Acknowledgments

- Jeff Rowberg for the MPU6050 library and initial codebase.
- Contributors to the MPU6050 library and the Arduino community for their valuable insights and support.
