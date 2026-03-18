# Predictive Maintenance of Physical Assets: Application to Wind Turbines

## Overview
This project develops the framework for a predictive maintenance system for wind turbines using condition-based monitoring, IoT infrastructure, and data-driven analysis. The integration of sensors and SCADA data with AI modeling highlighted the rotor and gearbox as high-risk while improving fault detection over traditional maintenance techniques.

## Problem
Traditional maintenance strategies tend to rely on fixed and scheduled repairs, often leaving early failures undetected. This leads to increased costs, unexpected failures, and reduced optimization of energy output.

## Objective
To design the framework of a predictive maintenance system that combines sensor data, analytics, and risk assessment to identify early signs of component failure and optimize device lifespan.

## Methodology
* Development of an IoT-based monitoring system using sensors and ESP32 for real-time data collection
* Cloud integration (AWS IoT, MQTT, Lambda) for scalable data processing
* Data processing with Python using IQR (Interquartile Range) outlier detection and physics-based relationships
* SCADA (Supervisory Control and Data Acquisition) data analysis for trends in system behavior
* Application of FMEA (Failure Mode and Effects Analysis) to identify and prioritize high-risk components

## Results
* Identification of rotor and gearbox as high-risk components
* Improved fault detection compared to existing preventive maintenance techniques

## Impact
This predictive maintenance system improves the reliability of wind turbine models, reduces operational costs, and supports sustainable energy production by adopting data-driven maintenance strategies.

## Future Work
* Improve accuracy of AI models with larger datasets
* Customize models for specific turbine types
