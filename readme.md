# STM32-Based Industrial Environmental Anomaly Detection System

## Overview

An embedded environmental monitoring prototype developed using an STM32 microcontroller to identify abnormal environmental conditions relevant to chemical-industry safety.

The system monitors temperature, humidity, and gas-related sensor readings, evaluates the measured parameters against configured thresholds, and identifies potentially unsafe environmental conditions.

## Objectives

- Monitor environmental parameters using multiple sensors.
- Identify abnormal temperature and humidity conditions.
- Detect unusual gas-sensor readings.
- Classify environmental conditions based on configured thresholds.
- Support early warning through the implemented alert or monitoring interface.

## Hardware Components

- **Microcontroller:** [Exact STM32 board/model]
- **Temperature and humidity sensor:** [Sensor model]
- **Gas sensor:** [Sensor model]
- **Alert/display components:** [List actual components]

## Software and Tools

- Embedded C
- STM32CubeIDE
- STM32 HAL / peripheral drivers [if used]
- [Other tools actually used]

## Working Principle

1. Sensors acquire environmental measurements.
2. The STM32 processes the sensor readings.
3. Readings are evaluated against configured thresholds.
4. Abnormal conditions are identified.
5. The system provides the alerts or visualizations implemented in the project.

## System Architecture

Environmental Sensors → STM32 → Data Processing → Threshold Evaluation → Alert / Monitoring Interface

## Repository Structure

- `Firmware/` — Microcontroller source code
- `Hardware/` — Circuit and component documentation
- `Dashboard/` — Monitoring interface, if applicable
- `Images/` — Prototype and demonstration images
- `Documentation/` — Architecture and project notes

## Limitations

This is an educational prototype, not a certified industrial gas detection or safety system. Actual hazardous-gas identification and concentration measurement depend on the sensors used, their calibration, and validation against suitable reference instruments.

## Future Improvements

- Sensor calibration and validation
- Historical data logging
- Remote monitoring
- Improved anomaly classification
- Industrial-grade sensing and safety-system integration


Electronics and Communication Engineering | Embedded Systems
