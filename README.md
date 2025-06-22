# 🛡️ Iron Dome Defense System Simulation

A **Pygame-based visual simulation** prototype replicating the behavior of an anti-rocket defense system inspired by the **Iron Dome of Israel**. This simulation demonstrates the detection, interception, and destruction of both conventional and hypersonic rockets targeting protected zones.

> **Disclaimer:** This project is created for educational and demonstration purposes only. It is not a real defense system and should not be interpreted as one.

---

## 🎯 Features

- 🔴 **Rocket Launch Simulation** (both conventional and hypersonic)
- 🟢 **Interceptor Missiles** launched from two defense domes
- 💥 **Mid-Air Explosions** on interception
- 🛑 **Dome Damage Calculation** when hypersonic missiles breach
- 📢 **Scrolling Disclaimer Banner** (e.g., prototype only)
- 🖼️ Realistic visuals with Iron Dome base image and animations

---

## 🛠️ Technologies Used

- **Python 3.10+**
- **Pygame**
- **Math & Random Libraries**

---

## 🚀 How It Works

1. **Rocket Generation**:
   - Randomly spawns conventional (red) and hypersonic (blue) rockets.
   - Each rocket is assigned a target zone (either of the two domes).

2. **Threat Detection**:
   - The system detects incoming conventional rockets within a detection radius.
   - Launches interceptors to neutralize the threat.

3. **Interceptor Launch**:
   - Green interceptor missiles are launched from the nearest dome.
   - Interception logic determines success based on hit distance and chance.

4. **Mid-Air Explosion**:
   - If a rocket is successfully intercepted, a **mid-air explosion** is triggered.

5. **Hypersonic Rocket Breach**:
   - If not intercepted and hits the dome, **damage is recorded** and visualized.

6. **Visuals & Feedback**:
   - Scrolling disclaimer alerts users this is a simulation.
   - Dome damage is shown dynamically under each base.

---

## 📸 Demo Preview

> _Add a screenshot or GIF here showing the simulation in action._

---

## 🧪 Usage

### 🔧 Requirements

- Python 3.10 or later
- Pygame (`pip install pygame`)

### ▶️ Run the Simulation

```bash
python iron_dome_simulation.py
```
## 📢 Disclaimer
This is a visual simulation prototype created solely for demonstration and educational purposes. It does not represent or simulate any real-world defense system. Inspired by the concept of the Israeli Iron Dome.

## ✨ Inspired By
- The Iron Dome missile defense system of Israel

- Real-time defense logic and threat interception

- Educational simulations of warfare systems using Python

## 📬 Contact
If you'd like to contribute or provide feedback:

- 💬 LinkedIn: Your Name

- 🌐 GitHub: YourUsername
