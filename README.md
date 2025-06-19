# 🔧 EASY-EDA PROJECTS

This repository contains basic PCB design projects created using **EasyEDA** — a powerful web-based EDA tool. The focus is on learning schematic design, component placement, routing, and generating 3D visualizations.

---

## 1️⃣ 555 Timer IC Basic PCB

This project demonstrates the creation of a **PCB layout for a 555 Timer IC (LM555DRG)** using **EasyEDA**.  
It serves as an introductory project for understanding PCB design for timer-based circuits.

---

### 📘 Objective

To design a simple 555 timer-based PCB in **Astable Mode**, which can be used for applications like blinking LEDs, tone generation, and basic timing circuits.

---

### 🧩 Circuit Diagram

#### 🔌 Schematic:

![Circuit Diagram](https://github.com/user-attachments/assets/0c1762fc-87fc-42d0-8ec6-041f6b37c23b)

---

### 🧾 Components Used

| Component | Value      | Description                           |
|----------|------------|---------------------------------------|
| U1       | LM555DRG   | 555 Timer IC                          |
| R1       | 1kΩ        | Timing resistor                       |
| R2       | 1kΩ        | Timing resistor                       |
| R3       | 1kΩ        | Output resistor for LED               |
| C1       | 0.1µF      | Timing capacitor                      |
| C2       | 0.1µF      | Decoupling capacitor                  |
| LED1     | LED-0805_R | Red LED (output indicator)            |
| Power    | +5V        | Power supply                          |
| GND      | -          | Ground                                |

---

### 🧭 PCB Routing

![Routing](https://github.com/user-attachments/assets/83967b36-62d7-4682-a141-30ef1ee1aa35)

- **Track Width**: 0.254 mm  
- Compact single-layer layout  
- Short, efficient traces for clean routing

---

### 🧱 3D View

![3D View](https://github.com/user-attachments/assets/ecbb3f6c-6eb3-41da-9e84-3b7751a2e5ca)

---

### ✅ Key Takeaways

- Understanding 555 Timer pinout and function  
- EasyEDA schematic and PCB design practice  
- Compact layout and visualization with 3D preview  
- Foundation for future timer-based projects

---

## 2️⃣ 7805 Voltage Regulator PCB

This project focuses on designing a **basic voltage regulator circuit** using the **7805 IC**. It converts an unregulated DC input (7–12V) into a stable +5V output.

---

### 📘 Theory

The **7805** is a linear voltage regulator that provides a fixed +5V output. It is ideal for supplying microcontrollers, sensors, and digital circuits.

**Supporting Components:**
- **C1 (Input capacitor)**: Filters input voltage and prevents noise
- **C2 (Output capacitor)**: Enhances regulator stability
- **LED with resistor**: Indicates that the 5V output is active

---

### 🧩 Circuit Diagram

#### 🔌 Schematic:

![Circuit Diagram](https://github.com/user-attachments/assets/5a415eb9-4b11-4f59-9394-d5f0a908eb72)

---

### 🧾 Components Used

| Component | Value         | Description                            |
|----------|---------------|----------------------------------------|
| U1       | 7805 (TO-220) | +5V Voltage Regulator IC               |
| R1       | 1kΩ           | Current-limiting resistor for LED      |
| C1       | 1µF           | Input filter capacitor                 |
| C2       | 1µF           | Output filter capacitor                |
| LED2     | LED-TH-5mm_R  | Red LED (power indicator)              |
| P1       | CONN-TH_2P    | Input terminal (DC IN)                 |
| P2       | CONN-TH_2P    | Output terminal (DC OUT)               |
| GND      | -             | Ground reference                       |

---

### 🧭 PCB Routing

![Routing](https://github.com/user-attachments/assets/d2a60a6c-a8cf-4cd3-bd2b-624b448053b0)

- **Track Width**: 0.254 mm  
- Single-layer routing  
- Power lines optimized for minimal voltage drop

---

### 🧱 3D View

![3D View](https://github.com/user-attachments/assets/589f915c-89cd-44aa-a93e-299ffc4fdd01)

---

### ✅ Key Takeaways

- Regulated power supply design  
- Use of 7805 in real-world applications  
- LED indication for output status  
- Clean, compact layout for easy prototyping

---

> 📌 These projects lay the groundwork for more advanced circuit designs such as microcontroller-based systems, sensor modules, and embedded hardware development.

