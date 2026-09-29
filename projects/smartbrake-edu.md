# SmartBrake Edu

**Type:** D4 Automotive Mechanical Engineering Final Project  
**Platform:** ESP32 DevKit V1  
**Repository:** [lidikun48/SmartBrake-Edu](https://github.com/lidikun48/SmartBrake-Edu)

## Project Purpose

SmartBrake Edu is an ESP32-based motorcycle braking telemetry prototype intended to support observation of braking practice in safety-riding education.

The system is designed to acquire and present:

- Relative front-brake pressure, 0–100%.
- Relative rear-brake pressure, 0–100%.
- Front-wheel speed.
- Rear-wheel speed.
- Front:rear braking-use distribution (F:R).
- Session data through a local web interface.

## Main Engineering Work

- Integration of two hydraulic pressure sensors.
- Integration of front/rear magnetic-pickup wheel-speed sensing.
- Relative pressure calibration using **Set Zero – Set Max**.
- Signal filtering for pressure and speed inputs.
- ESP32 local Access Point and HTTP web server.
- Responsive dashboard for phone, tablet, and laptop.
- Session logging, graphing, replay/history, and data export.
- Configuration storage using ESP32 Preferences/NVS.
- OTA firmware update.
- Hardware documentation and KiCad schematic/PCB work.

## Important Measurement Scope

Brake-pressure values are treated as **relative percentages**, not as calibrated absolute PSI/bar/MPa measurements. Wheel-speed data is used as supporting telemetry and is not presented as a certified speed measurement.

## Engineering Areas Demonstrated

- Embedded C++ / Arduino framework
- PlatformIO
- ESP32
- Analog sensor acquisition
- Pulse / wheel-speed measurement
- Signal filtering
- Local networking and web UI
- Data logging
- OTA update
- KiCad
- Technical documentation

---

[← Back to portfolio](../README.md)
