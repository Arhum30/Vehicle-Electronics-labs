# Ultrasonic Sensor and Linear Actuator Control

This project documents an automotive-inspired lab that combined ultrasonic distance measurement with actuator control for a hands-free boot opening concept.

## Overview

The aim of this lab was to:
- evaluate the performance of an ultrasonic sensor,
- determine its usable range and field of view,
- and use it to control a linear DC actuator through an Arduino-based system.

The application concept was similar to a hands-free vehicle boot-opening system.

## Tools and Technologies

- Arduino
- Ultrasonic sensor (URM37)
- Linear DC actuator
- IBT2 / BTS7960 H-Bridge
- Embedded programming
- Distance measurement and actuator control

## What was done

- Measured object distance using the URM37 ultrasonic sensor
- Evaluated horizontal and vertical field of view
- Determined the sensor’s practical usable range
- Connected the sensor to a linear actuator through an H-Bridge
- Implemented trigger-based actuator control logic in Arduino code
- Simulated an automatic open/close boot mechanism

## Key Findings

- The ultrasonic sensor delivered reliable measurements within its practical operating range
- The sensor maintained a broad detection cone suitable for object-trigger applications
- Beyond the practical range, invalid or unstable readings appeared
- The actuator control logic successfully toggled between extension and retraction
- The project demonstrated a simple embedded sensing-and-actuation workflow for an automotive use case

## Learning Outcomes

This lab strengthened practical understanding of:
- Sensor-based distance measurement
- Time-of-flight sensing
- Embedded control logic
- Actuator interfacing with H-Bridges
- Translating sensor input into physical system behavior

## Repository Contents

- Lab report / documentation
- Arduino code
- Measurement tables
- Actuator control logic summary
- Discussion and conclusions

## Note

This was a team-based university lab project completed as part of automotive engineering coursework.
