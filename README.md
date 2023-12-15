# BLDC Motor Driver for MIT Mini Cheetah Actuator

This BLDC (Brushless DC) Motor Driver is designed specifically for use with the MIT Mini Cheetah Actuator, inspired by the work of Ben Katz. The driver is intended to efficiently control the Mini Cheetah's actuators, enabling precise and agile movements.

## Overview

The BLDC Motor Driver is a crucial component in the Mini Cheetah Actuator system, responsible for managing the power and control signals sent to the brushless DC motors. It ensures smooth operation, speed control, and torque management for the actuators, contributing to the overall performance of the robotic system.

## Features

- **Brushless DC Motor Control:** Offers precise control over the motors used in the Mini Cheetah Actuator.
- **PWM (Pulse Width Modulation) Control:** Enables accurate speed control and torque management.
- **Communication Interface:** Interfaces with the main control system via a specified communication protocol (e.g., SPI, I2C, UART).
- **Overcurrent and Overvoltage Protection:** Safeguards the system and motors against potential damage due to excessive current or voltage.

## Hardware Requirements

- **BLDC Motors:** Compatible with the motors specified for the MIT Mini Cheetah Actuator.
- **Microcontroller or Control Board:** Interfaces with the driver to send control signals.
- **Power Supply:** Provides the necessary voltage and current for the motors.

## Installation and Setup

1. **Hardware Connections:** Connect the driver to the specified ports on the control board and motors as per the provided documentation or pinout details.
2. **Power Supply:** Ensure the power supply meets the voltage and current requirements of the motors.
3. **Control Interface:** Establish communication between the driver and the main control system using the designated communication protocol.
4. **Software Integration:** Implement the necessary control algorithms or software libraries to interact with the driver and control the motors effectively.

## Usage

- **Initialization:** Initialize the driver and configure the necessary parameters (e.g., PWM frequency, motor direction, etc.).
- **Control Commands:** Send control commands via the designated communication interface to adjust motor speed, direction, and torque as required.
- **Monitoring:** Implement monitoring mechanisms to keep track of motor performance, temperature, and any potential faults.

## Contributors

- Luis Avarez (CINVESTAV Guadalajara)

## License

This project is licensed under [MIT License](LICENSE.md).

## Acknowledgments

- Ben Katz (Original MIT Mini Cheetah Actuator Design)
