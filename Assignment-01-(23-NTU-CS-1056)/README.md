# Assignment 1 – Embedded IoT System  
**Name:** Muhammad Abdullah
**Reg No:** 23-NTU-CS-1056  
**Course:** Embedded IoT System  
**Instructor:** Nasir Mehmood  
**Date:** 23-Oct-2025  

---

## 🧭 Overview
This assignment contains **two ESP32-based projects** developed and tested on the **Wokwi Simulator**.  
Both projects demonstrate hardware interfacing, sensor input handling, and OLED-based visual feedback.

---

## 🔹 Task 1 – Multi-Device Control using ESP32 (LEDs, Buttons, Buzzer & OLED)

**Description:**  
ESP32 controls three LEDs, two buttons, and a buzzer with visual messages on an OLED.  
Buttons toggle LEDs and buzzer states, and OLED updates accordingly in real-time.

**Components Used:**
- ESP32 DevKitC V4  
- OLED 128x64 (I2C)  
- LEDs × 3  
- Buzzer × 1  
- Push Buttons × 2  
- 420Ω Resistors × 3  
- Jumper wires  

**Pin Map:**

| Component | Pin Name | GPIO No. |
|------------|-----------|----------|
| LED 1 | D2 | GPIO 2 |
| LED 2 | D4 | GPIO 4 |
| LED 3 | D5 | GPIO 5 |
| Button 1 | D26 | GPIO 26 |
| Button 2 | D27 | GPIO 27 |
| Buzzer | D15 | GPIO 15 |
| OLED SDA | SDA | GPIO 21 |
| OLED SCL | SCL | GPIO 22 |

**Wokwi Project Link:**  
🔗 [View Simulation on Wokwi](https://wokwi.com/projects/445735049640047617)

## Screenshots

Task 1 Output
![Task 1 Output](Task%2001/Pictures/Task-01.png)

Task 1 Hardware
![Task 1 Hardware](Task%2001/Pictures/Task%201%20Hardware.jpeg)


## 🔹 Task 2 – Button Press Duration Detection (Short / Long Press with OLED)

**Description:**  
This task detects **short and long button presses** using the ESP32.  
A short press toggles the LED, and a long press activates a buzzer. The OLED shows the feedback.

**Components Used:**
- ESP32 DevKitC V4  
- OLED 128x64 (I2C)  
- Push Button × 1  
- LED × 1  
- Buzzer × 1  
- Resistor × 1  

**Pin Map:**

| Component | Pin Name | GPIO No. |
|------------|-----------|----------|
| LED | D5 | GPIO 5 |
| Button | D25 | GPIO 25 |
| Buzzer | D18 | GPIO 18 |
| OLED SDA | SDA | GPIO 21 |
| OLED SCL | SCL | GPIO 22 |

**Wokwi Project Link:**  
🔗 [View Simulation on Wokwi](https://wokwi.com/projects/445792788940889089)

## Screenshots

Task 2 Output
![Task 2 Output](Task%2002/Pictures/Task-02.png)

Task 2 Hardware
![Task 2 Hardware](Task%2002/Pictures/Task%202%20Hardware.jpeg)


---



