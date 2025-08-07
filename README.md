# 🤖 Humanoid Robot Walking Simulation using 4 Servo Motors (Arduino + Tinkercad)

This project simulates basic walking movement in a humanoid robot using 4 servo motors connected to an Arduino Uno. The simulation is created using Tinkercad Circuits.

---

## 🔧 Hardware Used

- Arduino Uno R3
- 4x Servo Motors (SG90 or similar)
- Jumper Wires
- Power: 5V from Arduino

---

## ⚙️ Servo Motor Pins

| Servo Function       | Arduino Pin |
|----------------------|-------------|
| Right Hip (Servo 1)  | D3          |
| Left Hip (Servo 2)   | D5          |
| Right Knee (Servo 3) | D6          |
| Left Knee (Servo 4)  | D9          |

Each servo has 3 wires:
- Signal → connected to Arduino pin (D3, D5, D6, D9)
- VCC (Red) → Arduino 5V
- GND (Black/Brown) → Arduino GND

---

## 🧠 Project Behavior

1. All servos perform a sweep motion (0° → 180° and back) for 2 seconds.
2. After that, all servos hold at 90° (neutral standing position).
3. Then, the robot simulates walking by:
   - Lifting the right leg
   - Moving it forward
   - Lowering it
   - Repeating the same with the left leg

---

## 🧠 Walking Algorithm (Simplified)
