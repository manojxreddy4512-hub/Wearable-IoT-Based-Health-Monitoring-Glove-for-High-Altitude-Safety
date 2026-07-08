# Wearable-IoT-Based-Health-Monitoring-Glove-for-High-Altitude-Safety
Developed a wearable IoT-based health monitoring glove using ESP32, MAX30102, and LM35 to monitor heart rate, SpO₂, and body temperature. Displayed real-time data on an OLED screen, transmitted readings via Bluetooth, and generated alerts for abnormal health conditions.

## Overview

The Wearable IoT-Based Health Monitoring Glove is a portable healthcare system designed to monitor vital health parameters in real time. Built using an ESP32 microcontroller, MAX30102 pulse oximeter, LM35 temperature sensor, and OLED display, the device measures heart rate, SpO₂, and body temperature. The collected data is displayed on the OLED screen and transmitted to a mobile device via Bluetooth. The system also generates alerts when abnormal health conditions are detected, making it suitable for trekkers, high-altitude workers, and patients. :contentReference[oaicite:0]{index=0}

## Features

- Real-time heart rate monitoring
- Blood oxygen (SpO₂) measurement
- Body temperature monitoring
- OLED display for live readings
- Bluetooth data transmission
- Mobile monitoring
- Buzzer alerts for abnormal conditions
- Portable and low-cost wearable design

## Hardware Components

- ESP32 Development Board
- MAX30102 Pulse Oximeter Sensor
- LM35 Temperature Sensor
- OLED Display (SSD1306)
- Buzzer
- Li-Po Battery
- Breadboard
- Jumper Wires
- Wearable Glove

## Software Requirements

- Arduino IDE
- ESP32 Board Package
- MAX30102 Library
- Adafruit SSD1306 Library
- Adafruit GFX Library
- Bluetooth Serial Library
- Wire Library

## Technologies Used

- ESP32
- Arduino C++
- Bluetooth
- MAX30102 Sensor
- LM35 Sensor
- OLED Display
- Embedded Systems

## Working

1. ESP32 initializes all sensors and peripherals.
2. The MAX30102 measures heart rate and SpO₂.
3. The LM35 measures body temperature.
4. ESP32 processes the sensor data.
5. Health parameters are displayed on the OLED screen.
6. The readings are transmitted to a mobile phone via Bluetooth.
7. The system checks whether the values are within safe limits.
8. If abnormal values are detected, the buzzer is activated and a warning is displayed.
9. The monitoring process repeats continuously. :contentReference[oaicite:1]{index=1}

## System Architecture

MAX30102 Sensor

↓

ESP32

↓

OLED Display

↓

Bluetooth

↓

Mobile Phone

↓

Buzzer Alert

## Hardware Connections

MAX30102 → ESP32 (I2C)

LM35 → ESP32 Analog Pin

OLED Display → ESP32 (I2C)

Buzzer → ESP32 Digital Pin

Bluetooth → ESP32 Built-in Bluetooth

Battery → ESP32 Power Input

## Project Structure

```
Wearable-Health-Monitoring-Glove/
│
├── Arduino_Code/
│   └── health_monitoring_glove.ino
│
├── Images/
│   ├── block_diagram.png
│   ├── flowchart.png
│   ├── circuit.jpg
│   └── results.png
│
├── Documentation/
│   └── Project_Report.pdf
│
├── README.md
└── LICENSE
```

## Installation

Clone the repository.

```bash
git clone https://github.com/your-username/Wearable-Health-Monitoring-Glove.git
```

Open the project in Arduino IDE.

Install all required libraries.

Select the ESP32 board.

Connect the hardware according to the circuit diagram.

Upload the code to the ESP32.

Pair the ESP32 with your mobile phone using Bluetooth.

Open a Bluetooth terminal application to view live health data.

## Results

The system successfully monitors heart rate, blood oxygen saturation, and body temperature in real time. Health data is displayed on the OLED screen and transmitted to a mobile device through Bluetooth. The buzzer provides immediate alerts whenever abnormal health conditions are detected, enabling early intervention. :contentReference[oaicite:2]{index=2}

## Applications

- High-altitude safety
- Trekking and hiking
- Healthcare monitoring
- Remote patient monitoring
- Emergency health monitoring
- Wearable medical devices

## Future Improvements

- Wi-Fi cloud connectivity
- Mobile application
- GPS location tracking
- Emergency SOS feature
- Battery optimization
- AI-based health prediction
- Cloud data storage
- Continuous health analytics

## Authors

T. Manoj Kumar Reddy

Department of Electronics and Communication Engineering

SRM University-AP

## License

This project is developed for educational and research purposes.
