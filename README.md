# IoT-Based-Smart-Home-System-with-Assitive-Technology-
# 🏠 IoT Smart Home Monitoring System (Elderly Assistive Tech)

## Overview
A real-time IoT monitoring platform designed to assist elderly users, integrating:
- Two ESP32 sensor hubs (temperature, humidity, motion)
- 6-axis accelerometer for fall detection
- PyQt5 desktop dashboard
- SMS alerts via Twilio
- Wireless sensor communication (no Bluetooth, Wi-Fi based)

## Key Features
- Real-time sensor monitoring for 2 rooms
- Fall detection using accelerometer thresholding
- Automated SMS alert system
- Daily CSV logging
- Accessibility-focused smart home monitoring UI

## Components
|---|---|
| Microcontroller | ESP32 (Arduino IDE) |
| GUI | PyQt5 (Visual Studio / Python) |
| Sensors | Temp/Humidity, PIR, 6-axis accelerometer |
| Communication | Wi-Fi (no Bluetooth) |
| Alerts | Twilio API (SMS) |

## Project Structure
- `/Arduino` → ESP32 sensor firmware
- `/VisualStudio` → PyQt5 GUI application
- `/Diagrams` → System and PCB diagrams
- `/Results` → Demo screenshots and plots

## How to Run
1. Flash ESP32 boards using Arduino IDE from `/Arduino`
2. Install dependencies:
```bash
pip install pyqt5 matplotlib pandas twilio
```
3. Run GUI:
```bash
python main.py
```

## Future Improvements
- Add mobile app dashboard
- Integrate voice alerts
- Add AI fall prediction model
