# ESP8266 Passive Infared Sensor

A ESP8266 based system that transmits a status message (via ESPnow) to a central communication point upon waking from a deep sleep state. A PIR device drives a pulsed pull-down circuit that briefly pulls the ESP8266s reset pin to ground, thus waking the ESP8266 from deep sleep.
![IMG_20231213_234426628](https://github.com/CountZero1066/ESP8266-Deep-sleep-with-PIR-wake-and-ESPnow-status-transmission/assets/32957102/a802df7e-11ba-47ba-9c24-18f2b4b126d0)

# Hardware

- MCP1700-3302E regulator
- capacitors: 1x 100uF, 1x 1uF, 1x 1nF 
- resistors : 1x 1kΩ, 1x 2kΩ
- 2N222 transistor
- Diode

# Wake Circuit Diagram
![pir wake sch](https://github.com/CountZero1066/ESP8266-Deep-sleep-with-PIR-wake-and-ESPnow-status-transmission/assets/32957102/4bc91ea5-0fe3-4910-b9c5-2ae5ead85b7f)

![wake cct](https://github.com/CountZero1066/ESP8266-Deep-sleep-with-PIR-wake-and-ESPnow-status-transmission/assets/32957102/a34e655d-9f50-4b42-b1df-d2531aba9548)
