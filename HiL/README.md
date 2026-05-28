# Hardware-in-the-Loop (HiL) ECU Validation with CANoe and CANdb++

This project documents a Hardware-in-the-Loop automotive lab focused on ECU validation, CAN communication analysis, and fault injection.

## Overview

The goal of this lab was to evaluate the behavior of an ESP control unit under realistic but controlled simulation conditions using a HiL environment.

The project combined:
- CAN communication fundamentals
- CANoe and CANdb++ analysis
- ECU fault injection
- Diagnostic interpretation
- Validation of controller behavior under abnormal conditions

## Tools and Technologies

- CarMaker
- CANoe
- CANdb++
- HiL testing
- DVA (Direct Variable Access)
- ECU diagnostics
- CAN trace analysis

## What was done

- Tested ECU behavior under different supply voltages
- Observed warning lamp and diagnostic behavior under undervoltage conditions
- Injected wheel-speed sensor faults using DVA
- Inspected DBC message and signal definitions in CANdb++
- Analyzed protocol-level communication issues in CANoe
- Reviewed statistics, graphics, and logged signal behavior for repeatability analysis

## Key Findings

- Lower supply voltage caused more degraded and protective ECU behavior
- Implausible wheel-speed inputs were detected reliably by the ESP ECU
- Multiple sensor faults generated clear diagnostic entries for affected channels
- CANdb++ enabled interpretation of raw CAN data into meaningful engineering signals
- CANoe trace analysis showed repeatable ErrorFrame and Stuff Error events at bus level

## Learning Outcomes

This lab strengthened practical understanding of:
- ECU validation workflows
- CAN-based automotive communication
- Signal-level vs. protocol-level fault diagnosis
- Repeatable fault injection in simulation
- Diagnostic reasoning in vehicle electronics

## Repository Contents

- Lab report / documentation
- Diagnostic screenshots
- CANoe and CANdb++ analysis material
- Fault injection summary
- Validation conclusions

## Note

This was a team-based university lab project completed as part of automotive engineering coursework.
