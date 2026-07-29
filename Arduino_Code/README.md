# Air Mouse Using ESP32 and MPU6050

![Platform](https://img.shields.io/badge/Platform-ESP32-blue)
![Language](https://img.shields.io/badge/Language-Arduino_C++-orange)
![Sensor](https://img.shields.io/badge/Sensor-MPU6050-green)
![Bluetooth](https://img.shields.io/badge/Communication-Bluetooth_LE-success)

## 📌 Project Overview

This project implements a Bluetooth-enabled Air Mouse using an ESP32 development board and an MPU6050 motion sensor. The ESP32 acts as a Bluetooth HID mouse, allowing users to control the computer cursor by moving the device in the air. Two push buttons provide left-click and right-click functionality.

## ✨ Features

- Bluetooth HID Mouse
- Motion-based cursor control
- Left-click button
- Right-click button
- Wireless operation
- Lightweight and low-cost design

## 🛠 Hardware Used

- ESP32 DevKit V1
- MPU6050 (GY-521)
- 2 × Push Buttons
- Breadboard
- Jumper Wires
- Micro USB Cable

## 💻 Software Used

- Arduino IDE
- ESP32 Board Package
- BleMouse Library
- MPU6050 Library

## 🔌 Pin Connections

| ESP32 | MPU6050 |
|-------|----------|
| 3.3V | VCC |
| GND | GND |
| GPIO21 | SDA |
| GPIO22 | SCL |

### Push Buttons

| Function | GPIO |
|----------|------|
| Left Click | GPIO18 |
| Right Click | GPIO19 |

## ⚙️ Working Principle

1. ESP32 reads gyroscope values from the MPU6050.
2. Hand movements are converted into cursor movement.
3. ESP32 transmits mouse data using Bluetooth HID.
4. Push buttons perform left-click and right-click operations.

## 📂 Repository Structure

Arduino_Code/
Hardware/
Images/
Demo/
README.md
LICENSE

## 🚀 Future Improvements

- Cursor smoothing
- Gesture recognition
- Scroll functionality
- Rechargeable battery support
- Adjustable sensitivity

## 👨‍💻 Authors

**Omkar I Angadi Saikiran R Baddi Kiran Y Alur Omkareshwar M Kamblimath **

Electronics & Communication Engineering

ESP32 | Embedded Systems | FPGA | Verilog | VLSI
