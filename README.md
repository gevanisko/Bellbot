# BellBot

This repository contains the hardware design files, documentation, and supporting resources for the BellBot project. BellBot is an autonomous luggage transportation robot intended to use sensing, mapping, wireless control, onboard data storage, and motor control to move luggage through indoor environments.

The hardware in this repository is developed across multiple board revisions. Each version is used to test, validate, and improve different parts of the system, including power regulation, peripheral integration, motor control, communication, and future onboard intelligence.

## Project Overview

The long-term goal of BellBot is to create a robotic luggage transportation system capable of navigating indoor environments. The system is designed around Simultaneous Localization and Mapping (SLAM), LiDAR sensing, inertial measurement, Bluetooth control, onboard logging, and multi-directional motor control.

Early board revisions focus on creating a reliable minimum viable product (MVP). Later revisions are intended to improve size, integration, efficiency, and performance.

## Core Goals

The BellBot hardware is designed to support:

- Autonomous navigation through mapped environments
- LiDAR-based obstacle detection and mapping
- Remote control through Bluetooth or another wireless interface
- Onboard storage for sensor data, logs, and system debugging
- Motor control for movement in a 2D plane
- Multiple regulated voltage rails for sensors, logic, and motors
- Expandability for future sensors, memory, and processing hardware

## Hardware Features

Across the project revisions, the BellBot hardware may include:

| Feature | Purpose |
|---|---|
| STM32 Microcontroller | Main control platform for peripherals, motor control, and system logic |
| LiDAR | 2D scanning for mapping, localization, and obstacle detection |
| IMU | Acceleration, angular velocity, magnetic field, and orientation sensing |
| Bluetooth / Wireless Module | Remote control, debugging, or wireless communication |
| SPI Flash / SD Storage | Onboard storage for sensor data and logs |
| Servo / Motor PWM Outputs | Control signals for the robot drive system |
| 3.3 V Rail | Logic-level supply for MCU and low-voltage peripherals |
| 5 V Rail | Peripheral and module power |
| 8 V Rail | Servo or motor power |
| I2C / SPI / UART / Quad-SPI Breakouts | Expansion for additional sensors, memory, or communication modules |
| Battery Charging and Protection | Portable operation and safe lithium-ion battery use |

## Board Revisions

This repository is intended to support multiple hardware revisions. Each revision may include different component choices, layouts, and design improvements.
