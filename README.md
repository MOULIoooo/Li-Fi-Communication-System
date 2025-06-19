# Li-Fi-Communication-System
# 💡 Li-Fi Communication System (Light Fidelity)

This project demonstrates a low-cost, high-speed **Li-Fi (Light Fidelity)** system that enables wireless communication using **visible LED light** and a **photodiode receiver**. Data is transmitted in the form of light pulses (ON/OFF states), making it secure, interference-free, and an innovative alternative to traditional RF-based systems like Wi-Fi.

---

## 📌 Components Used

- Arduino Uno (2x) – Transmitter and Receiver
- LED (White/IR) – for data transmission
- Photodiode or Light Dependent Resistor (LDR) – for reception
- Resistors (1K, 10K)
- Breadboard and jumper wires
- Serial Monitor / LCD Display (optional for output)

---

## ⚙️ Working Principle

1. **Transmitter Side**:
   - Data (characters) is sent via **LED** using digital HIGH/LOW pulses.
2. **Receiver Side**:
   - **Photodiode or LDR** detects variations in light intensity.
   - Arduino decodes these into binary and converts to readable text.
3. **No RF signal** is used, so it’s highly secure and immune to electromagnetic interference.

---

## 🔧 How to Use

1. Connect the **Transmitter Arduino** with an LED on a digital pin.
2. Connect the **Receiver Arduino** with a photodiode and analog/digital pin.
3. Run transmitter code on one Arduino and receiver code on the other.
4. Use **Serial Monitor** to view received characters.

---

## 📸 Project Images

*Add LED & photodiode circuit setup images.*

---

## 📹 Demo Video

[Watch the demo](https://your-demo-link)

---

## 🧠 Developed By

👨‍💻 Mouli S  
St. Joseph's College of Engineering  
Department of EEE
