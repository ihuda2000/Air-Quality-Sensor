# Air-Quality-Sensor
This project is a Raspberry Pi Zero WH–based air quality monitoring system using an Enviro+ and PMS5003 sensor to measure temperature, humidity, VOCs, and particulate matter in real time.  

## Overview
- Designed and implemented as part of a personal IoT exploration.
- Collected and displayed sensor readings in real time.
- Future extensions included cloud logging and dashboard visualization.

## Hardware
- Raspberry Pi Zero WH  
- Enviro+ environmental sensor board  
- PMS5003 particulate matter sensor  

## Implementation
- Data captured via Python scripts using sensor libraries.
- Displayed live readings on Raspberry Pi terminal and optional web interface.
- Supported export to CSV for further analysis.

## Data Logging Format

The sensor logs data in CSV format (`air_quality_log.csv`) with the following columns:

timestamp_iso, temperature_c, humidity_pct, pressure_hpa,
gas_oxidising_kohm, gas_reducing_kohm, gas_nh3_kohm,
pm1_ugm3, pm2_5_ugm3, pm10_ugm3


## Lessons Learned
- Experience with I²C and UART communication protocols.  
- Worked with real-world sensor calibration and environmental variability.  
- Built skills in IoT prototyping and Raspberry Pi development.
