# 🧑‍🔬 Fingerprint Attendance Alerting System

An automated **Fingerprint-based Attendance Management System** that records attendance using biometric authentication and generates **email alerts** for absentees. The system also provides **Telegram bot integration** for individual attendance queries.

This project is designed to reduce manual effort, improve accuracy, and automate attendance monitoring in educational and organizational environments.

---

## 📌 Project Overview

The **Fingerprint Attendance Alerting System** automates the attendance process by:
- Capturing fingerprints from users
- Matching them with preloaded fingerprint data
- Recording attendance automatically
- Generating email alerts for students with attendance below threshold
- Providing individual attendance details via Telegram bot

The system integrates **Arduino UNO**, **Fingerprint Sensor**, and **Raspberry Pi** to handle biometric authentication, data processing, and alerting.

---

## 🎯 Objectives

- Collect fingerprints from users
- Match fingerprints with stored records
- Automatically record attendance
- Identify absentees
- Send email alerts for attendance below 75%
- Provide attendance details through Telegram bot
- Reduce manual intervention and errors

---

## 🧩 Components Used

| Component | Description |
|--------|-------------|
| Arduino UNO | Interfaces fingerprint sensor and communicates with Raspberry Pi |
| Fingerprint Sensor | Captures and matches fingerprint data |
| Raspberry Pi 3B+ | Main processing unit running Linux and Python scripts |
| 5-inch Display | Displays system output |
| Power Bank | Supplies power to Arduino and Raspberry Pi |
| Jumper Wires | Hardware connections |

---

## 🔌 Hardware Role Description

### Arduino UNO
- Powers the fingerprint sensor
- Communicates fingerprint data to Raspberry Pi via USB serial

### Fingerprint Sensor
- Captures fingerprint data
- Stores up to 300 fingerprints
- Sends matching status to Arduino

### Raspberry Pi 3B+
- Runs Linux OS
- Executes Python and shell scripts
- Hosts email alert system and Telegram bot
- Stores all attendance data

### Display
- Provides user-friendly visual output

---

## 🔗 Connections

- Fingerprint sensor connected to Arduino UNO
- Arduino UNO connected to Raspberry Pi via USB
- Raspberry Pi connected to display via DSI interface
- Power bank supplies power to Arduino and Raspberry Pi

---

## 🧪 Test Case (TS)

`TS` stands for **Test Case**.  
A separate branch named `ts` was created to demonstrate the system using **11 preloaded fingerprints**, representing a classroom scenario.

Example Test Users:
