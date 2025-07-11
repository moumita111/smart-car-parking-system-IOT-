# 🚗 Smart Car Parking System using Arduino

This project is a simple and smart **Car Parking System** built with Arduino, designed to automate parking slot management. It uses IR sensors to detect vehicle movement, an LCD to display available slots, and a servo motor to control the gate.

---

## ✨ Features

- Detects vehicle entry and exit automatically
- Displays available slots on an LCD screen
- Servo-controlled gate (opens and closes automatically)
- "Parking Full" alert when no slots left
- Real-time updates on Serial Monitor

---

## 💡 How It Works

- **IR Sensor 1 (Entry):** Detects cars entering the parking area.
- **IR Sensor 2 (Exit):** Detects cars leaving.
- **Servo Motor:** Controls the gate mechanism.
- **LCD Display:** Shows welcome messages, available slots, or "Parking Full" status.

---

## 🛠️ Hardware Components

- Arduino board (e.g., Arduino Uno)
- 2 × IR sensors
- 1 × Servo motor
- 1 × LCD display (16x2 with I2C module)
- Jumper wires
- Breadboard
- Power supply

---

## 🔌 Pin Connections

| Component    | Arduino Pin |
|---------------|-------------|
| IR Sensor 1   | D2          |
| IR Sensor 2   | D3          |
| Servo Motor   | D4          |
| LCD (I2C)     | SDA, SCL   |

> 💬 **Note:** Default I2C address for LCD is `0x27`.

---

## 📝 How to Use

1. **Clone or download this repository.**

2. **Open the code in Arduino IDE.**

3. **Upload the code to your Arduino board.**

4. **Connect all components as per the pin connections above.**

5. **Open the Serial Monitor to see real-time status logs.**

6. **Test by blocking/unblocking IR sensors to simulate car entry/exit.**

---



## 💬 Acknowledgments

Thanks to all Arduino and electronics tutorials that inspired this project.  
Happy building! 💡✨
