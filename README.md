# Chemical Gas Detection Bot

## Overview
An IoT-based chemical gas detection robot using ESP32, MQ135, MQ2, and Blynk IoT platform.

## Features
- Mobile control using Blynk
- WiFi communication
- Real-time gas monitoring
- Smoke and LPG detection
- Air quality monitoring
- Motorized robotic movement
- Gas alert notification

## Hardware Used
- ESP32
- MQ135 Sensor
- MQ2 Sensor
- Motor Driver
- DC Motors
- Battery

## Software Used
- Arduino IDE
- Blynk IoT
- Embedded C++

## Pin Configuration

### MQ Sensors
| Sensor | ESP32 Pin |
|--------|------------|
| MQ135 | GPIO34 |
| MQ2 | GPIO35 |

### Motor Driver
| Driver Pin | ESP32 |
|------------|---------|
| ENA | GPIO25 |
| IN1 | GPIO26 |
| IN2 | GPIO27 |
| ENB | GPIO14 |
| IN3 | GPIO12 |
| IN4 | GPIO13 |

## Working Principle
The ESP32 receives joystick commands from the Blynk mobile app through WiFi.  
MQ135 and MQ2 sensors continuously monitor air quality and harmful gases.  
If gas concentration exceeds threshold values, alerts are sent through Blynk.

## Applications
- Industrial safety
- Chemical plant monitoring
- Hazardous gas detection
- Remote surveillance robots

