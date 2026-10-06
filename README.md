# AAI05 Robot Car

INF2004 embedded systems project using the Raspberry Pi Pico W and Robo Pico.

The design covers line following, barcode commands, encoder-controlled movement, ultrasonic obstacle scans, hump-height estimation, and WiFi/MQTT telemetry.

## Design review

- [Week 6 report (PDF)](docs/AAI05_Week6_Design_Review.pdf)
- [Week 6 report (Word)](docs/AAI05_Week6_Design_Review.docx)
- [Wiring schematic](docs/figures/01-wiring-schematic.png)
- [Debug probe connections](docs/figures/02-debug-probe.png)
- [Interrupt capture paths](docs/figures/03-interrupt-capture.png)
- [Task interactions](docs/figures/04-task-interactions.png)
- [System and subsystem statecharts](docs/figures/05-statecharts.png)

This repository contains the Week 6 design documents. Firmware is not included yet. Timing values and calibration settings are test targets; hardware assumptions and estimator accuracy still require validation.

## Team responsibilities

| Member | Responsibility |
| --- | --- |
| You Yan | Mission, line following, barcode and integration |
| Daniyal | Motor drive, encoders, ultrasonic scan and servo avoidance |
| Patrick | IMU calibration, hump detection and height estimation |
| Brian | WiFi, MQTT telemetry, commands and recovery |
