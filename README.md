# Color-Based Sorting Machine using TIA Portal & Factory I/O

## 📌 Project Overview

This repository presents a **color-based sorting machine** implemented using **Siemens TIA Portal** and simulated in **Factory I/O**. The project focuses on PLC-based industrial automation, where objects are detected by color and sorted into different paths accordingly.

The PLC program is written entirely in **Ladder Logic (LAD)** and validated through a realistic 3D simulation environment by linking **TIA Portal with Factory I/O**.

---

## 🏭 System Description

The system consists of:

* A **main conveyor belt** transporting boxes
* **Two color sensors**, each associated with a dedicated pusher
* **Two pushers**, used to divert boxes to separate paths
* **Secondary conveyors** that receive sorted boxes

### Sorting Logic

* When a **green box** is detected by the first color sensor, the corresponding **pusher is activated** to move the box onto its designated conveyor path.
* When a **blue box** is detected by the second color sensor, the second **pusher diverts the box** onto a different conveyor.
* Boxes that do not match the specified colors continue on the main conveyor.

All decision-making and actuator control are handled through **Ladder Logic (LAD)** within TIA Portal.

---

## 🛠️ Tools & Technologies

* **Siemens TIA Portal** – PLC programming
* **Factory I/O** – Industrial simulation
* **PLC Programming Language**: Ladder Logic (LAD)
* **Virtual Sensors & Actuators**

---

## 🎥 Project Demo

A demonstration video is included showing:

* The Factory I/O simulation setup
* Real-time interaction between sensors and pushers
* Correct sorting of green and blue boxes onto separate conveyors

📁 *Refer to the attached simulation video in this repository.*

---

## 📂 Repository Contents

```
├── TIA_Portal_Project/        # PLC Ladder Logic program and project template
├── Simulation_Video/         # Video demonstrating the sorting process
├── README.md                 # Project documentation
```

---

## ⚙️ How to Run the Project

1. Open the **TIA Portal project** using a compatible TIA Portal version, this project used V16 of the template
2. Launch **Factory I/O** and load the sorting machine scene
3. Configure communication between **TIA Portal (PLCSIM / PLCSIM Advanced)** and Factory I/O
4. Start the PLC simulation
5. Run Factory I/O and observe the color-based sorting behavior

---

## 🎯 Learning Outcomes

* Ladder Logic (LAD) programming for industrial automation
* Sensor-based control systems
* Actuator control using pushers
* PLC and Factory I/O integration for virtual commissioning

---


## ⭐ If you find this project useful

Feel free to ⭐ star the repository or fork it for learning and experimentation.
