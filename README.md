# ESP32-IR-Object-Detection
An ESP32-based object detection project using an IR sensor and LED output. This project demonstrates GPIO interfacing, digital input/output, sensor integration, and basic embedded programming using ESP32.


# ESP32 IR Object Detection 🔧📡

## 📌 Overview

This project demonstrates a simple **object detection system using ESP32 and an IR sensor**.

The IR sensor detects the presence of an object and sends a digital signal to the ESP32. Based on the sensor input, the ESP32 processes the signal and controls an LED as an output indication.

This project was developed as part of my **Embedded Systems Training at Kalpataru Institute of Technology under Magnus**.

---

## 🎯 Objectives

- Understand ESP32 GPIO programming
- Interface an IR sensor with ESP32
- Detect objects using an IR sensor
- Control an LED based on sensor input
- Understand digital HIGH and LOW signals
- Practice embedded programming
- Simulate and test the circuit using Wokwi

---

## 🛠️ Components Used

- ESP32 Development Board
- IR Sensor
- LED
- Resistor
- Jumper Wires
- Breadboard
- USB Cable

---

## 🔄 Working Principle

The system works according to the following flow:

**Object → IR Sensor → ESP32 GPIO → Program Logic → LED Output**

When an object is detected, the IR sensor changes its digital output. The ESP32 reads this signal through a GPIO pin and controls the LED according to the programmed logic.

---

## ⚙️ Technologies Used

- ESP32
- Arduino IDE
- Embedded C / Arduino Programming
- GPIO
- IR Sensor
- Wokwi Simulator

---

## 💻 Programming Concept

The ESP32 continuously reads the digital output of the IR sensor.

If an object is detected:

```text
IR Sensor → ESP32 → LED ON
