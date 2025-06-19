# EASY-EDA PROJECT: 555 Timer IC Basic PCB
---
## 1) 555 Timer IC Basic PCB
This project demonstrates the creation of a **PCB layout for a 555 Timer IC (LM555DRG)** using **EasyEDA**. The aim is to understand the fundamentals of PCB design for a commonly used IC and its supporting components.


## 📘 Objective

Design and layout a simple PCB circuit using **LM555 Timer IC** in EasyEDA. This layout can be used for various timer-based applications later.

---

## 🧩 Circuit Diagram

### Schematic:

![Circuit Diagram](https://github.com/user-attachments/assets/0c1762fc-87fc-42d0-8ec6-041f6b37c23b)

This is a basic 555 Timer setup prepared for PCB design practice and learning routing skills in EasyEDA.

---

### 🧾 Components Used:
| Component | Value      | Description                           |
|----------|------------|---------------------------------------|
| U1       | LM555DRG   | 555 Timer IC                          |
| R1       | 1kΩ        | Timing resistor                       |
| R2       | 1kΩ        | Timing resistor                       |
| R3       | 1kΩ        | Resistor for output/LED               |
| C1       | 0.1µF      | Timing capacitor                      |
| C2       | 0.1µF      | Decoupling capacitor (optional)       |
| LED1     | LED-0805_R | Red LED (used as an output indicator) |
| Power    | +5V        | Power supply                          |
| GND      | -          | Ground reference                      |

---

## 🔧 PCB Routing

![Routing](https://github.com/user-attachments/assets/83967b36-62d7-4682-a141-30ef1ee1aa35)

- **Routing Width**: `0.254 mm`
- Neat and compact single-layer PCB routing for beginner practice.
- All components are placed considering minimal track length and easy soldering.

---

## 🧱 3D View

![3D View](https://github.com/user-attachments/assets/ecbb3f6c-6eb3-41da-9e84-3b7751a2e5ca)

The 3D preview shows how the final board will appear after fabrication and assembly.

---

## ✅ Key Learning Outcomes:
- How to place components and make connections in EasyEDA
- Setting track width and optimizing layout
- Visualizing the board in 3D for manufacturing

---

> 🔁 This PCB serves as a base for future projects using the 555 timer, such as blinking LEDs, timers, tone generators, and more.

## 2️⃣ 7805 Voltage Regulator PCB

This project demonstrates the design of a **basic voltage regulator PCB** using the **7805 voltage regulator IC** in EasyEDA. It converts a higher DC input voltage (e.g., 7–12V) down to a stable **+5V output**, commonly used in digital circuits and microcontroller systems.

---

## 📘 Theory

The **7805** is a 3-terminal **linear voltage regulator** that provides a constant +5V output. It's ideal for powering logic circuits and microcontrollers from a higher voltage source like a 9V battery or a 12V adapter.

**Why use capacitors?**
- **C1 (Input side):** Smooths the input voltage and absorbs transients.
- **C2 (Output side):** Improves transient response and stability.
- **LED with resistor:** Indicates that the 5V output is active.

---

## 🧩 Circuit Diagram

### Schematic:

![Circuit Diagram](https://github.com/user-attachments/assets/5a415eb9-4b11-4f59-9394-d5f0a908eb72)

---

### 🧾 Components Used:
| Component | Value         | Description                              |
|----------|---------------|------------------------------------------|
| U1       | 7805 (TO-220) | Voltage Regulator IC (+5V output)        |
| R1       | 1kΩ           | Current limiting resistor for LED        |
| C1       | 1µF           | Input side capacitor                     |
| C2       | 1µF           | Output side capacitor                    |
| LED2     | LED-TH-5mm_R  | 5mm Red LED                              |
| P1       | CONN-TH_2P    | Input terminal (DC IN)                   |
| P2       | CONN-TH_2P    | Output terminal (DC OUT)                 |
| GND      | -             | Ground reference                         |

---

## 🔧 PCB Routing

![Routing](https://github.com/user-attachments/assets/d2a60a6c-a8cf-4cd3-bd2b-624b448053b0)

- **Track Width:** 0.254 mm
- Clean single-layer routing
- Power paths kept short for low resistance and low noise

---

## 🧱 3D View

![3D View](https://github.com/user-attachments/assets/589f915c-89cd-44aa-a93e-299ffc4fdd01)

This 3D model helps visualize how the final PCB will appear post-manufacturing.

---

## ✅ Key Learning Outcomes:
- Designing a power supply circuit in EasyEDA
- Using voltage regulators in PCB design
- Importance of capacitors in voltage regulation circuits
- Power supply visualization and terminal placement



