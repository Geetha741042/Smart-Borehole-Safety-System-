# Smart Borehole Safety System

> An IoT-based automated safety system designed to prevent accidents caused by open and unprotected boreholes using real-time monitoring, intelligent detection, and automatic protection.

## Table of Contents
- Project Overview
- Problem Statement
- Objectives
- Features
- System Architecture
- Hardware Components
- Software Requirements
- Technologies Used
- Working Principle
- Project Structure
- Installation
- Results
- Future Enhancements

---

# Project Overview

Open and abandoned boreholes pose serious safety hazards to humans and animals, especially in rural areas and construction sites. Traditional protection methods rely on manual covers and periodic monitoring, which are often ineffective during emergencies.

The Smart Borehole Safety System is an IoT-based solution that continuously monitors the area around a borehole using PIR sensors and automatically controls a safety cover using a servo motor. The system sends real-time alerts through the ESP32 microcontroller and supports remote monitoring. Additional features such as motion-triggered image capture, night mode, and risk assessment improve the overall safety and reliability of the system.

---

# Problem Statement

Unprotected boreholes can cause fatal accidents due to the lack of continuous monitoring and immediate safety mechanisms. Existing solutions depend on manual intervention, making them unreliable and inefficient.

---

# Objectives

- Detect motion around the borehole in real time.
- Automatically open and close the protective cover.
- Send instant IoT alerts when motion is detected.
- Provide manual control during maintenance or emergencies.
- Improve borehole safety using intelligent automation.

---

# Features

- 360° Motion Detection using four PIR sensors
- ESP32-based IoT Monitoring
- Automatic Servo Motor Controlled Safety Cover
- Manual Override Buttons
- Real-Time Alerts
- Motion Triggered Camera
- Night Safety Mode
- Risk Assessment (Low, Medium, High)
- Energy Efficient Design
- Cost-Effective Solution

# Hardware Components

- ESP32 Development Board
- PIR Motion Sensors (4)
- Servo Motor
- Camera Module (ESP32-CAM/Compatible)
- Push Buttons
- LED Indicators
- Power Supply
- Connecting Wires
- Breadboard/PCB
- Borehole Model

---

# Software Requirements

- Arduino IDE
- ESP32 Board Package
- Blynk / MQTT / Firebase (depending on implementation)
- Arduino Libraries
- Wi-Fi Connection

---

# Technologies Used

- Internet of Things (IoT)
- Embedded Systems
- ESP32
- Arduino Programming
- Motion Detection
- Servo Motor Automation
- Wireless Communication

---

# Working Principle

1. Four PIR sensors continuously monitor the borehole area.
2. Motion detected from any direction is sent to the ESP32.
3. The ESP32 processes the sensor data.
4. The system sends an instant alert through the IoT platform.
5. The servo motor automatically operates the protective cover.
6. The camera captures images when movement is detected.
7. The system classifies the detected activity into Low, Medium, or High risk.
8. Manual buttons allow emergency operation when required.

---

# Installation

1. Install Arduino IDE.
2. Install ESP32 Board Manager.
3. Install the required libraries.
4. Open the project in Arduino IDE.
5. Configure Wi-Fi credentials.
6. Upload the code to the ESP32.
7. Assemble the hardware.
8. Power on the system.

---

# Usage

- Power the ESP32.
- Connect the device to Wi-Fi.
- Place the PIR sensors around the borehole.
- Monitor alerts through the IoT dashboard.
- Observe automatic cover operation when motion is detected.
- Use manual buttons for emergency control if required.

---

# Results

- Successfully detects motion around the borehole.
- Sends real-time alerts.
- Automatically operates the safety cover.
- Supports remote monitoring.
- Reduces the risk of borehole accidents.
- Provides reliable and continuous safety monitoring.

---

# Future Enhancements

- AI-based human and animal identification.
- GSM/SMS emergency notifications.
- Solar-powered operation.
- Cloud data storage and analytics.
- Mobile application.
- GPS location tracking.
- Voice alarm and emergency siren.


## Acknowledgements

We express our sincere gratitude to our project guide, department faculty members, and institution for their valuable guidance and support throughout the development of this project.

## Project Images

- Project Model
- Hardware Setup
- Working Demonstration
- Output Screenshots
