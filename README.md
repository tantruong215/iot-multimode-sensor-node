# Multi-Protocol IoT Sensor Node

Designed a low-power environmental monitoring node capable of dynamically switching between Wi-Fi and LoRaWAN based on signal strength and battery level.

## Hardware Components
- ESP32 microcontroller
- SHT31 (temperature/humidity)
- BH1750 (ambient light)
- Li-Ion battery with charging circuit

## Features
- 1 Hz sampling rate
- Dynamic switch: Wi-Fi ↔ LoRaWAN (RSSI and battery threshold)
- Wi-Fi: HTTPS and MQTT
- LoRaWAN: SF7, 125 kHz, TTN integration

## Backend + Visualization
- Node-RED for flow-based processing
- InfluxDB for time-series storage
- Grafana dashboards with alerting rules

## Tools Used
- PlatformIO + Arduino Framework
- Node-RED
- TTN Console

## Project Status
In Progress – Summer 2025
