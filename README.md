# washing-machine-iot
ESP32-based washing machine monitoring system


## Overview

This project aims to monitor washing machine activity using an ESP32 and an ADXL345 accelerometer.

## Motivation

I want to solve the problem of not knowing when a shared washing machine has finished its cycle.

## Goals
- Detect whether a washing machine is running or stopped.
- Avoid false detections using a time threshold.
- Send notifications over Wi-Fi in a later development stage.
## Hardware
- ESP32 development board
- ADXL345 accelerometer
- USB cable and jumper wires
- Breadboard
## Current Progress
- [x] Practiced basic C/C++ programming in Wokwi.
- [x] Created a simulated vibration monitoring program.
- [x] Implemented a five-second stop detection check.
- [x] Tested the ESP32 hardware.
- [x] Connected the ADXL345 sensor.
- [x] Vertified I2C communication
- [ ] Read three-axis acceleration.
- [ ] Measure real washing machine vibration.
- [ ] Detect washing machine operating status.
- [ ] Implement Wi-Fi notifications.
## Development Log

See the docs folder for progress reports.

## Current Status

This project is currently the prototype stage.

I successed connecting the ESP32 and ADXL345 and verified I2C communication.

I need to obtain three-axis accelation data from sensor next time.
