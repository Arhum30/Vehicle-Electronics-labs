# Adaptive Cruise Control (ACC) Sensor Evaluation

This project documents an automotive lab focused on evaluating radar sensor configurations for an Adaptive Cruise Control (ACC) system using CarMaker.

## Overview

The objective of this lab was to compare three radar sensor configurations under multiple driving scenarios and determine which sensor provides the best overall performance for ACC operation.

The evaluated scenarios included:
- Highway
- Curve 30 m
- Curve 100 m
- Curve 400 m
- Hill

Each scenario was simulated with three radar variants that differed in:
- Horizontal field of view (FoV)
- Vertical field of view (FoV)
- Maximum detection range

## Tools and Technologies

- CarMaker
- Automotive sensor simulation
- Radar parameter analysis
- MATLAB / graph interpretation
- Engineering evaluation and weighted scoring

## What was done

- Simulated five ACC-relevant driving scenarios in CarMaker
- Compared three radar configurations with different range and FoV parameters
- Analyzed target detection distance and following behavior
- Evaluated whether the ACC system fulfilled distance-keeping requirements
- Applied a weighted scoring approach to compare overall sensor suitability

## Key Findings

- Long radar range was important for highway safety and early target detection
- Wider azimuth improved performance in tight curve scenarios
- Wider elevation improved tracking on hill profiles
- Sensor 2 provided the best compromise between range, azimuth, and elevation
- Sensor 2 was identified as the recommended sensor for the ACC system

## Learning Outcomes

This lab strengthened practical understanding of:
- ACC system behavior
- Radar sensor trade-offs
- Vehicle scenario-based validation
- Safety-oriented engineering evaluation
- Structured comparison of automotive sensor configurations

## Repository Contents

- Lab report / documentation
- Scenario analysis
- Result screenshots and graphs
- Evaluation summary

## Note

This was a team-based university lab project completed as part of automotive engineering coursework.
