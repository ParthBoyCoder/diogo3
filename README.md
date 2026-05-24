# Project Diogo 3 (Enviro-Mod)

Project Diogo 3 is an autonomous environmental analysis and testing rover that is currently under development. It performs a localized atmospheric and soil analysis using many sensors that we are going to talk about.

The project combines robotics, embedded systems, environmental sensing, and future terrain interaction systems into a single mobile platform capable of collecting real-time environmental data (along with the GPS coordinates the data was collected from) across varied terrain.

Unlike traditional stationary weather stations, Diogo 3 focuses on spatial environmental analysis — allowing environmental conditions to be measured dynamically across different locations instead of a single fixed point.

---

# Core System Architecture

The rover is built on a custom AWD robotic chassis powered by BO geared motors and controlled using a hybrid dual-processing architecture consisting of:

- Raspberry Pi Zero W
- ESP32-CAM
- DRV8833 motor driver
- NEO-6M GPS module

The Raspberry Pi Zero W acts as the primary processing and logging system, while the ESP32-CAM handles visual telemetry and lightweight control operations.

---

# Environmental Monitoring Payload

The platform is being expanded into a modular environmental sensing system capable of monitoring:

## Atmospheric Conditions
- Temperature
- Humidity
- Barometric pressure
- UV intensity
- Dust concentration
- Air quality & gas presence
- Noise pollution

## Soil Conditions
- Soil moisture
- Soil temperature
- Future NPK analysis

## Imagine seeing a beauty like this in a well designed dashboard

| Timestamp | Latitude | Longitude | Temperature | Humidity | Pressure | UV Intensity | Dust / PM | Gas Detection | Noise Level | Soil Moisture | Soil Temperature |
|---|---|---|---|---|---|---|---|---|---|---|---|
| 14:32:21 | 22.5726 | 88.3639 | 31.4°C | 68% RH | 1004 hPa | 5.8 UV Index | 42 µg/m³ | Moderate | 63 dB | 52% | 27.1°C |
| 14:33:02 | 22.5728 | 88.3641 | 31.1°C | 69% RH | 1003 hPa | 5.6 UV Index | 39 µg/m³ | Low | 61 dB | 55% | 26.8°C |
| 14:33:46 | 22.5730 | 88.3644 | 30.9°C | 70% RH | 1003 hPa | 5.4 UV Index | 44 µg/m³ | Moderate | 65 dB | 53% | 26.9°C |

More data can be streamed and dont even try to forget that the ESP32CAM POV can also be streamed! :)
---

# Automated Soil Sampling System

One of the primary goals of the project is the development of an automated soil interaction subsystem.

During operation, the rover will periodically stop and deploy or insert soil sensors directly into the ground using a custom mechanical lowering mechanism currently being designed.

The mechanical system will most probably consist of a stepper motor and a mechanism that converts the motion to linear.

After measurements are collected, the sensors retract and the rover resumes traversal.

This allows the platform to perform both atmospheric and subsurface environmental analysis autonomously.

---

# Current Development Status

Current Development Status Is Updated In SubFolder Logs

---

# Long-Term Vision

Future development goals include:
- autonomous navigation,
- environmental heatmap generation,
- live telemetry dashboards,
- GPS-tagged environmental mapping,
- advanced sensor fusion,
- and terrain-aware traversal systems.
- NPK level testing with an advanced (and expensive (yikes)) sensor. That will also be inserted with soil insertion mechanism along with the 2 other current sensors.

---

# Repository Purpose

This repository serves as a public engineering log documenting the design, development, testing, and evolution of Project Diogo 3.

---

# Rover Architecture

<img width="1280" height="620" alt="design" src="https://github.com/user-attachments/assets/0e73f53a-bb2a-47af-b43c-8b95019350cc" />

---

# Rover Prototype Images And Base Rover Details

Check "rover" subfolder!

---

# Author

Parthib Banerjee  
Class 11 Student | Robotics Enthusiast | Developer
