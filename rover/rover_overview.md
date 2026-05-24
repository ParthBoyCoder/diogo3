# Diogo 3 Base Rover

## Overview
The Diogo 3 rover base is a custom-built AWD robotic platform designed for environmental and agricultural data collection missions.

This rover serves as the primary mobility subsystem of Project Diogo 3 (Enviro-Mod), enabling autonomous traversal across localized terrain while carrying multiple environmental sensing modules.

---

## Current Hardware

### Mobility
- AWD robotic chassis
- 4x BO geared motors

### Compute & Control
- Raspberry Pi Zero W
- ESP32-CAM
- DRV8833 motor driver

### Navigation
- NEO-6M GPS Module (Not shown in picture as I am working on it currently!)

### Power System
- 7.4V dual 18650 battery pack for drivetrain
- Separate USB power bank for onboard compute systems

---

## Planned Sensor Payload
The rover is being expanded into a modular environmental sensing platform with support for:

- Temperature & humidity sensing
- Barometric pressure sensing
- UV intensity sensing
- Dust / particulate sensing
- Gas detection
- Noise pollution analysis
- Soil moisture sensing
- Soil temperature sensing
- Future NPK analysis subsystem

---

## Planned Soil Deployment System
A future subsystem currently under development will allow the rover to autonomously lower soil sensors into the ground during stationary sampling intervals.

After measurements are taken, the mechanism retracts and the rover resumes traversal.

---

## Current Status
Project currently under active development.

This repository documents the ongoing design, prototyping, testing, and integration progress of the Diogo 3 platform.
