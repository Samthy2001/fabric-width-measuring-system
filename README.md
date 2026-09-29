# Automated Fabric Width Measuring System
<img width="1983" height="793" alt="ChatGPT Image Sep 30, 2026, 02_20_03 AM" src="https://github.com/user-attachments/assets/48e0cbda-44cd-4194-976f-8ce51c59a523" />

## Overview

The **Automated Fabric Width Measuring System** is a mechatronics-based industrial automation project developed to measure fabric width accurately during the production process.

The system integrates **infrared sensing, motor control, embedded programming, user interaction, and data logging** to automate fabric measurement and improve quality monitoring.

The prototype uses an **Arduino Mega 2560** as the main controller, infrared sensors for edge detection, motorized rollers for fabric movement, and an LCD interface for real-time measurement display.

---

# Project Objectives

- Develop an automated fabric width measurement system.
- Replace manual measurement methods with sensor-based measurement.
- Detect fabric edges using infrared sensors.
- Control fabric movement using motors.
- Display measurement results in real time.
- Store measurement data for analysis.
- Improve accuracy and efficiency in textile quality control.

---

# System Architecture and Data Flow

The system consists of sensing, processing, actuation, user interface, and data logging modules.

The Arduino Mega 2560 receives sensor inputs, processes measurement data, controls motors, displays results, and communicates data to a computer.

```
              Fabric Input
                   |
                   ↓
        Infrared Sensor Array
        (Fabric Edge Detection)
                   |
                   ↓
          Arduino Mega 2560
        (Processing & Control)
                   |
     --------------------------------
     |              |               |
     ↓              ↓               ↓
 Motor Control   LCD Display    Data Logging
     |              |               |
     ↓              ↓               ↓
 Gear Motors    Measurement     PLX-DAQ /
 Fabric Feed    Output          Excel Storage

                   |
                   ↓

        Fabric Width Measurement Result
```
<img width="1536" height="1024" alt="ChatGPT Image Sep 30, 2026, 02_21_33 AM" src="https://github.com/user-attachments/assets/eb52e49c-d892-473a-888b-bf7db18810d5" />


---

# Hardware Components

| Component | Purpose |
|---|---|
| Arduino Mega 2560 | Main processing and control unit |
| Infrared Sensor Array | Detects fabric edges |
| Gear Motors | Controls fabric movement |
| Servo Motors | Mechanical adjustment mechanism |
| LCD Display | Shows measurement values |
| 4x4 Keypad | User input and settings |
| Buzzer | Warning notification |
| Motor Driver | Motor control |
| Power Supply | System operation |

---

# Software Technologies

- Arduino IDE
- Embedded C/C++
- Serial Communication
- PLX-DAQ
- Microsoft Excel Data Logging

---

# Working Principle

## 1. Fabric Feeding

The fabric is moved through the measurement system using motorized rollers.

## 2. Edge Detection

Infrared sensors detect the position of fabric edges.

## 3. Data Processing

The Arduino Mega processes sensor readings and calculates the fabric width.

## 4. Display Output

The measured width value is displayed on the LCD screen.

## 5. Data Recording

Measurement values are transferred to a computer and stored using serial communication and data logging.

---

# Main Features

## Automated Width Measurement

The system automatically measures fabric width without manual measurement.

## Infrared-Based Detection

Infrared sensors provide accurate fabric edge detection.

## Real-Time Monitoring

The LCD provides immediate measurement feedback to the operator.

## Data Logging

Measurement data can be recorded for further analysis and quality monitoring.

## Industrial Application

The system can support textile production environments by improving measurement efficiency.

---

# My Contribution

- Designed the automated measurement system.
- Integrated Arduino Mega control architecture.
- Implemented infrared sensor-based measurement.
- Developed motor control functionality.
- Integrated LCD and keypad user interface.
- Implemented serial data communication.
- Tested measurement operation and system performance.

---

# Project Output

The developed prototype demonstrates:

- Automated fabric width measurement
- Sensor-based edge detection
- Motorized fabric handling
- Real-time measurement display
- Digital data recording

The project demonstrates the application of embedded systems and automation in textile quality control.

---

# Challenges

- Improving sensor measurement accuracy.
- Maintaining stable fabric movement.
- Reducing measurement errors caused by fabric variation.
- Synchronizing sensors and motor operation.
- Managing reliable data communication.

---

# Future Improvements

- Add AI-based fabric defect detection.
- Improve measurement accuracy using advanced sensors.
- Develop cloud-based production monitoring.
- Add touchscreen user interface.
- Integrate Industrial IoT features.
- Connect multiple measurement stations.

---

# Repository Structure

```
fabric-width-measuring-system

├── README.md
├── LICENSE
│
├── images
│   ├── banner.png
│   └── system-architecture.png
│
├── Arduino
│   └── Fabric_Width_Code.ino
│
├── Data
│   └── Measurement_Results
│
└── Documentation
```

---

# Technologies Used

- Arduino Mega 2560
- Infrared Sensors
- Embedded Systems
- Motor Control
- Automation
- Serial Communication
- Data Logging
- Industrial IoT

---

# Author

**Samthy Shuaib**

Mechatronics Engineering Student

Interested in:

- Robotics
- Embedded Systems
- Automation
- IoT
- Intelligent Systems

GitHub:

https://github.com/Samthy2001
