## Fire & Smoke Detection Alarm System

## Overview
The system integrates a flame sensor and an MQ-2 gas/smoke sensor with an Arduino Uno (ATmega328P). It continuously reads sensor data, compares it against predefined thresholds, and activates a buzzer alarm when fire or dangerous smoke levels are detected. An I2C LCD optionally displays real-time status messages. 

## How It Works
The MQ-2 sensor provides analog smoke/gas readings processed via the built-in ADC
The flame sensor provides a digital signal on fire detection
If either reading exceeds the safe threshold, the buzzer activates immediately
When conditions return to normal, the buzzer deactivates automatically

## Components
Arduino UNO (ATmega328P)
MQ-2 Gas / Smoke Sensor
Flame Sensor (IR)
I2C 16×2 LCD Display
Buzzer
Battery

## Software
Arduino IDE — Embedded C programming
Proteus 8 Professional — Circuit simulation

## Key Features
Real-time continuous environmental monitoring
Dual-sensor detection — smoke and flame
Instant buzzer alert with minimal latency
LCD status display
Low-cost build (under PKR 3,000)
Suitable for homes, labs, and small offices

## Limitations
MQ-2 requires ~20 seconds warm-up after power-on
Detection range limited to ~1–2 meters
No remote notifications (no Wi-Fi/GSM)
No battery backup for power failure scenarios

## Future Improvements
Add ESP8266/ESP32 for Wi-Fi alerts via SMS or mobile app
Integrate DHT11 for temperature and humidity-aware detection
Implement multi-zone sensor nodes
Add UPS battery backup circuit
Apply ML-based adaptive threshold calibration

## Team
Laveeza Fatima · Muhammad Soban Zamir · Mohammed Imaan Khan · Abuzar Shafaat
