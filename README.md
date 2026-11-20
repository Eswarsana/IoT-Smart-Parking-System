# IoT-Based Smart Parking System

## Project Overview

The IoT-Based Smart Parking System is designed to detect available and occupied parking spaces using Arduino Uno and IR sensors. The system identifies empty parking spaces and indicates their availability through blinking LED indicators.

The Arduino processes the sensor data and transmits parking-status information to the Telnet mobile application through a Bluetooth module. The application receives and stores the collected data and provides parking availability information to the surveillance team.

## Objectives

- Detect available and occupied parking spaces using IR sensors.
- Monitor parking-slot availability automatically.
- Indicate empty parking spaces using LED indicators.
- Transmit parking-status information wirelessly.
- Reduce manual parking-space monitoring.

## Hardware Components

| S.No | Component | Purpose |
|---|---|---|
| 1 | Arduino Uno | Main controller |
| 2 | IR Sensors | Detect vehicle presence |
| 3 | Bluetooth Module | Wireless communication |
| 4 | LED Indicators | Indicate available parking spaces |
| 5 | Connecting Wires | Hardware connections |
| 6 | Power Supply | Powers the system |

## Software Requirements

- Arduino IDE
- Telnet Mobile Application
- Arduino Programming (C/C++)

## Working Principle

### 1. Arduino Uno
Acts as the main controller and processes the information received from the IR sensors.

### 2. IR Sensors
Detect whether a parking space is occupied or empty by sensing the presence of vehicles.

### 3. LED Indicators
Blink to indicate available parking spaces, helping identify empty slots.

### 4. Bluetooth Module
Establishes wireless communication between the Arduino Uno and the mobile device.

### 5. Telnet Mobile Application
Receives and stores parking-status data transmitted through the Bluetooth module and provides availability information to the surveillance team.

## System Workflow

1. IR sensors continuously monitor the parking spaces.
2. The sensors detect whether vehicles are present.
3. Arduino Uno processes the IR sensor readings.
4. LED indicators blink when parking spaces are empty.
5. Bluetooth transmits the parking information to the mobile application.
6. The Telnet application receives and records the data.
7. Parking availability information is communicated to the surveillance team.

## Arduino Pin Configuration

| S.No | Component | Arduino Uno Pin |
|---|---|---|
| 1 | Bluetooth RX | D2 |
| 2 | Bluetooth TX | D3 |
| 3 | IR Sensor – Slot 1 | D4 |
| 4 | IR Sensor – Slot 2 | D5 |
| 5 | IR Sensor – Slot 3 | D6 |
| 6 | LED – Slot 1 | D7 |
| 7 | LED – Slot 2 | D8 |
| 8 | LED – Slot 3 | D9 |


## Technologies Used

- Internet of Things (IoT)
- Arduino Uno
- IR Sensor Technology
- Bluetooth Communication
- Embedded C/C++
- LED Indicators
- Telnet Mobile Application

## Key Features

- Automatic parking-space detection using IR sensors.
- Empty and occupied slot identification.
- LED-based parking availability indication.
- Wireless data transmission.
- Mobile-based parking-status monitoring.
- Reduced manual monitoring.

## Project Outcome

Developed an IoT-based Smart Parking prototype that detects available parking spaces using IR sensors, indicates empty slots using LEDs, and transmits parking-status information to a mobile application for monitoring.

## Author

**Sana Omkareswar**
