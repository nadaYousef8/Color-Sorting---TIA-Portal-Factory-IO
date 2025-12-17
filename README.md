# Color-Based Sorting Machine using TIA Portal & Factory I/O

## 📌 Project Overview

This repository presents a **color-based sorting machine** programmed using **Siemens TIA Portal** and simulated through **Factory I/O**. The project demonstrates an industrial automation task where objects are detected, classified by color, and sorted accordingly using PLC logic.

The system was fully tested in a virtual environment by linking **TIA Portal with Factory I/O**, allowing realistic sensor-actuator interaction and verification of control logic without physical hardware.

---

## 🏭 System Description

The sorting machine operates as follows:

* Objects move along a conveyor belt
* A color sensor detects the object color
* The PLC processes sensor data
* Actuators (pushers/diverters) route each object to its corresponding conveyor based on color

The control logic is implemented using **PLC programming** within TIA Portal, following industrial automation practices.

---

## 🛠️ Tools & Technologies

* **Siemens TIA Portal** (PLC programming)
* **Factory I/O** (3D industrial simulation)
* **PLC Languages**: Ladder Logic (LAD) 
* **Virtual Sensors & Actuators**

---

## 🎥 Project Demo

A demonstration video is included in this repository showing:

* Factory I/O simulation environment
* Real-time PLC control via TIA Portal
* Object detection and color-based sorting behavior

📁 *See the video file attached in this repository.*

---

## 📂 Repository Contents

```
├── TIA_Portal_Project/        # PLC project template and program files
├── Simulation_Video/         # Demonstration video of the system
├── README.md                 # Project documentation
```
---
### PLC–Simulation Integration
The PLC program was connected to Factory I/O using Siemens PLCSIM.
Digital inputs and outputs were mapped between Factory I/O sensors,
conveyors, and pushers, enabling real-time control and validation of
the Ladder Logic program.
---

## ⚙️ How to Run the Project

1. Open the **TIA Portal project template** using the appropriate TIA Portal version, for this project V16 was used 
2. Open **Factory I/O** and load the corresponding scene
3. Configure communication between TIA Portal and Factory I/O (PLCSIM / PLCSIM Advanced)
4. Start the PLC simulation
5. Run Factory I/O and observe the sorting process

## ⭐ If you find this project useful

Feel free to ⭐ star the repository or fork it for learning and experimentation.
