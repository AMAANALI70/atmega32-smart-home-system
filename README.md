# 🏠 Smart Home System using ATmega32

A microcontroller-based **Smart Home Automation System** built using **ATmega32**, combining a **Smart Door Lock** and a **Smart Fan** controller. This project was developed as part of our Microcontroller Applications course and demonstrates home security and convenience through embedded systems.

## 📌 Overview

This project includes two major modules:

### 🔐 Smart Door Lock
- Password-based door locking system
- LCD display for status messages
- Keypad input for password entry
- Buzzer alert for incorrect attempts
- Servo motor control to lock/unlock door
- Password reset/change option

### 🌬️ Smart Fan Controller
- Adjustable fan speed based on user preference
- Input via keypad or preset logic
- LCD display shows selected speed
- PWM-based fan control (software or hardware)
- Energy-efficient design and user-friendly interface

## ⚙️ Hardware Components

- ATmega32 Microcontroller
- 4x4 Matrix Keypad
- 16x2 LCD Display
- Servo Motor (for door lock)
- Buzzer
- DC Fan or PWM-controlled motor
- Motor Driver IC (e.g., L293D or MOSFET circuit)
- Power Supply (5V regulated)
- Breadboard & connecting wires

## 🧰 Tools Used

- AVR-GCC / Atmel Studio / MikroC
- USBASP / AVR Programmer
- Proteus (for simulation, optional)
