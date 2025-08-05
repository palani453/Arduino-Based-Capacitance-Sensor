# Arduino-Based Capacitance Sensor

This project presents a liquid capacitance measurement system developed using an Arduino Uno. It is designed to analyze the dielectric properties of various liquids in a non-invasive, repeatable manner. The setup utilizes a cavity with copper plates that are charged and discharged by the Arduino. Real-time capacitance values are displayed on a 16x2 I2C LCD screen, offering a user-friendly and portable liquid analysis tool.

---

## 📘 Project Overview

- **Objective**: To measure the dielectric constant of liquids using capacitive sensing techniques.
- **Microcontroller**: Arduino Uno (ATmega328P based).
- **User Interface**: I2C-based 16x2 LCD for real-time display of capacitance in picofarads (pF).

---

## ✨ Key Features

- Real-time liquid capacitance measurement.
- User-friendly LCD interface.
- Compact and portable: powered via USB or 9V battery.
- Reusable and easy-to-clean liquid cavity.
- Accurate and repeatable results.

---

## 🔧 Hardware Components

- Arduino Uno board
- Custom-built plexiglass cavity with copper foil plates
- 16x2 I2C LCD Display
- Pull-down resistors
- Jumper wires
- USB cable or 9V battery power supply

---

## ⚙️ Working Principle

1. **Baseline Reading**: With an empty cavity, the system records a baseline capacitance value (air dielectric).
2. **Sample Loading**: A liquid sample is poured into the cavity.
3. **Capacitance Variation**: The Arduino detects capacitance changes due to the dielectric properties of the liquid.
4. **Display**: The real-time capacitance value is shown on the LCD in pF.

Different liquids affect the electric field differently, allowing users to identify or compare their dielectric characteristics.

---

## 🧪 Setup Instructions

1. **Power On**: Connect the Arduino via USB or a 9V battery.
2. **Observe Baseline**: Note the LCD reading with the cavity empty.
3. **Add Sample**: Fill the cavity with the test liquid without leaving air gaps.
4. **Read Output**: View the updated capacitance value on the display.
5. **Prevent Interference**: Avoid touching the cavity or wires during operation to ensure measurement accuracy.

---

## 📊 Sample Output (Approximate Values)

| Liquid Sample   | Capacitance (pF) | Dielectric Effect     |
|------------------|------------------|------------------------|
| Air (Empty Cavity) | ~24             | Baseline reference     |
| Tap Water         | ~36             | High dielectric constant |
| Apple Juice       | ~31             | Moderate dielectric     |

---

## 🚀 Future Improvements

- Add pH and TDS sensors for more comprehensive liquid analysis.
- Incorporate data logging and wireless connectivity (e.g., Bluetooth or Wi-Fi).
- Expand the system to test solid or semi-solid dielectric materials.

---

## 👤 Author

**Palaniappan Balasubramanian**  
Madras Institute of Technology, Anna University

---

## 📚 References

- [Capacitance Meter Circuit – Circuit Digest](https://circuitdigest.com/microcontroller-projects/arduino-capacitance-meter-circuit)
- [LiquidCrystal I2C Library – GitHub](https://github.com/fdebrabander/Arduino-LiquidCrystal-I2C-library)
- [Understanding Dielectrics – Electricity & Magnetism](https://www.electricity-magnetism.org/what-is-a-dielectric/)
