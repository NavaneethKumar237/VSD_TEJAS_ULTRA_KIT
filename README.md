# VSDSquadron Ultra Educational Kit

## 🚀 Learn Electronics. Program RISC-V. Build Real Products.

The **VSDSquadron Ultra Educational Kit** is a hands-on educational platform built around the **VSDSquadron Ultra RISC-V development board**.

The kit uses a **custom-designed PCB** with built-in LEDs, input/output interfaces, energy measurement circuits, and additional expansion/PDM pins.

It is designed to provide students with a structured learning journey — starting from a simple **LED experiment** and gradually progressing toward a complete **Smart Energy Meter** project.

---

## 🎯 Project Vision

The main goal of this kit is to make embedded systems and electronics learning more practical and project-oriented.

Instead of directly giving students a complex final project, the kit follows a step-by-step approach where every experiment introduces a new concept.

```text
Basic Electronics
        ↓
LED & GPIO
        ↓
Digital Inputs
        ↓
Sensors
        ↓
ADC
        ↓
Voltage Measurement
        ↓
Current Measurement
        ↓
Power Calculation
        ↓
Energy Calculation
        ↓
SMART ENERGY METER
```

By the end of the learning journey, students understand how individual electronic components, embedded programming, sensors, ADC and real-world measurements can be combined into a complete engineering system.

---

# 🔧 About the Hardware

The platform is built around the **VSDSquadron Ultra**, a RISC-V based development platform.

A **custom educational PCB** has been designed to work with the VSDSquadron Ultra and provide students with dedicated hardware for learning and experimentation.

The custom PCB reduces the need for repeated breadboard connections and provides an organized platform for performing experiments.

---

## 🧩 Custom PCB Features

The custom educational PCB includes:

* On-board LEDs
* Digital input/output interfaces
* Energy measurement section
* Voltage sensing interface
* Current sensing interface
* Additional PDM/expansion pins
* Easily accessible GPIO connections
* Dedicated experiment interfaces
* Connections for the final Energy Meter project

The PCB is designed so that students can start with very simple experiments and progressively use the same hardware platform for more advanced applications.

---

# 🧠 Learning Objectives

After completing the experiments in this kit, students will gain practical knowledge of:

* Basic electronics
* Digital electronics
* GPIO programming
* Embedded programming
* Digital input and output
* Sensor interfacing
* Analog signals
* ADC
* Voltage measurement
* Current measurement
* Power calculation
* Energy calculation
* RISC-V based embedded systems
* Hardware and software integration
* PCB-based product development
* Real-world engineering projects

---

# 📚 Learning Path

## Level 1 — Getting Started

Students begin by understanding the development board and programming environment.

### Topics

* Introduction to VSDSquadron Ultra
* Hardware overview
* Software setup
* Board connection
* First program
* Program upload
* Basic program structure

---

# 💡 Level 2 — Basic Electronics

Students begin with simple LED and GPIO experiments.

### Experiments

1. LED Blink
2. Multiple LED Control
3. Push Button
4. LED + Push Button
5. Buzzer
6. Basic GPIO Experiments

### Concepts

* Digital HIGH
* Digital LOW
* GPIO
* Digital input
* Digital output
* Resistors
* Basic circuit understanding
* Embedded programming fundamentals

---

# 🔌 Level 3 — GPIO & Sensors

After understanding basic GPIO, students move toward real-world inputs.

### Topics

* Digital sensors
* Analog sensors
* Sensor interfacing
* GPIO input
* GPIO output
* Reading sensor values
* Processing sensor data
* Controlling outputs based on sensor inputs

---

# 📈 Level 4 — ADC & Analog Measurement

Students are introduced to analog signals and ADC.

### Topics

* Analog vs digital signals
* ADC fundamentals
* Reading analog values
* ADC conversion
* Sensor scaling
* Calibration
* Real-world measurement

This stage prepares students for electrical measurement.

---

# ⚡ Level 5 — Electrical Measurement

Students now move from general sensors to electrical parameter measurement.

### Topics

* Voltage measurement
* Current measurement
* ADC-based measurement
* Sensor calibration
* Power calculation
* Energy calculation

Basic electrical relationships:

```text
Power = Voltage × Current
```

and:

```text
Energy = Power × Time
```

Students use these concepts to understand how electrical energy consumption can be monitored using an embedded system.

---

# ⚡ Level 6 — Smart Energy Meter

The final stage of the learning journey is the **Smart Energy Meter**.

This project combines the concepts learned throughout the previous experiments.

### System Concept

```text
             ELECTRICAL LOAD
                   │
          ┌────────┴────────┐
          │                 │
   Voltage Sensor     Current Sensor
          │                 │
          └────────┬────────┘
                   │
                  ADC
                   │
                   ↓
          VSDSquadron Ultra
                   │
                   ↓
           Data Processing
                   │
                   ↓
          Power Calculation
                   │
                   ↓
          Energy Calculation
                   │
                   ↓
          Energy Dashboard
```

---

# 🧮 Energy Meter Concept

The energy meter uses electrical measurements and embedded processing to calculate useful energy parameters.

The basic calculation is:

```text
Power = Voltage × Current
```

Energy can then be calculated based on power and time:

```text
Energy = Power × Time
```

The final system demonstrates how sensor data can be acquired, processed and converted into meaningful electrical information.

---

# 🏆 Final Project

## Smart Energy Meter

The final project integrates:

* Voltage sensing
* Current sensing
* ADC acquisition
* Embedded programming
* Data processing
* Power calculation
* Energy calculation
* Data visualization

The final project is intended to demonstrate how a RISC-V-based embedded platform can be used to develop a practical real-world application.

---

# 🧪 Experiment List

| No. | Experiment           | Main Concept         |
| --- | -------------------- | -------------------- |
| 01  | LED Blink            | GPIO Output          |
| 02  | Multiple LED Control | Digital Output       |
| 03  | Push Button          | Digital Input        |
| 04  | LED + Push Button    | Input / Output       |
| 05  | Buzzer               | GPIO Control         |
| 06  | Sensor Interface     | Sensor Interfacing   |
| 07  | Analog Input         | ADC                  |
| 08  | Voltage Measurement  | Voltage Sensing      |
| 09  | Current Measurement  | Current Sensing      |
| 10  | Power Calculation    | Embedded Processing  |
| 11  | Energy Calculation   | Energy Measurement   |
| 12  | Smart Energy Meter   | Complete Application |

---

# 🛠️ Hardware Platform

The kit uses the **VSDSquadron Ultra** as its main processing platform.

The platform provides interfaces that can be used for embedded experiments, sensor interfacing and expansion.

### Platform capabilities include:

* RISC-V based processing
* GPIO
* ADC
* UART
* SPI
* I2C
* Expansion interfaces
* USB interface
* Wireless capability through the onboard wireless platform

For official information:

**VSDSquadron Ultra:**
https://www.vlsisystemdesign.com/vsdsquadronultra/

**VSDSquadron GitHub:**
https://github.com/VSDSquadron

---

# 🔩 Custom PCB

The custom PCB is the main educational interface between the student and the VSDSquadron Ultra.

Instead of connecting every component individually on a breadboard, students can use the dedicated hardware provided on the PCB.

### The PCB provides:

```text
VSDSquadron Ultra
        │
        ├── LEDs
        │
        ├── Digital Inputs
        │
        ├── Sensor Interfaces
        │
        ├── ADC Interfaces
        │
        ├── Voltage Measurement
        │
        ├── Current Measurement
        │
        ├── Energy Measurement
        │
        └── Expansion / PDM Pins
```

---

# 📌 Hardware Documentation

The repository will contain complete hardware documentation including:

* PCB overview
* Circuit diagram
* Schematic
* PCB layout
* Pin configuration
* GPIO mapping
* Sensor connections
* Voltage measurement circuit
* Current measurement circuit
* Expansion/PDM pin details
* Bill of Materials
* PCB fabrication files

---

# 💻 Software Documentation

Each experiment will contain the required firmware and explanation.

Every experiment will follow a common structure:

```text
Experiment
│
├── Objective
├── Components Required
├── Circuit Connection
├── Pin Configuration
├── Source Code
├── Code Explanation
├── Expected Output
├── Troubleshooting
├── Student Exercise
└── Challenge Task
```

---

# 📁 Repository Structure

```text
VSDSquadron-Ultra-Educational-Kit/
│
├── README.md
│
├── 01_Getting_Started/
│   ├── Introduction.md
│   ├── Hardware_Overview.md
│   ├── Software_Setup.md
│   └── First_Program/
│
├── 02_Basic_Electronics/
│   ├── 01_LED_Blink/
│   ├── 02_Multiple_LED/
│   ├── 03_Push_Button/
│   ├── 04_LED_Button/
│   └── 05_Buzzer/
│
├── 03_GPIO_Experiments/
│   ├── Digital_Input/
│   ├── Digital_Output/
│   └── GPIO_Exercises/
│
├── 04_Sensors/
│   ├── Digital_Sensors/
│   ├── Analog_Sensors/
│   └── ADC/
│
├── 05_Electrical_Measurement/
│   ├── Voltage_Measurement/
│   ├── Current_Measurement/
│   └── Power_Calculation/
│
├── 06_Smart_Energy_Meter/
│   ├── Firmware/
│   ├── Circuit/
│   ├── Dashboard/
│   ├── Calibration/
│   └── Documentation/
│
├── Hardware/
│   ├── Schematics/
│   ├── PCB/
│   ├── Pinout/
│   └── BOM/
│
├── Images/
│
├── Videos/
│
└── Datasheets/
```

---

# 🎓 Educational Methodology

The kit follows a simple learning methodology:

```text
LEARN
  ↓
UNDERSTAND
  ↓
BUILD
  ↓
EXPERIMENT
  ↓
DEBUG
  ↓
INTEGRATE
  ↓
CREATE
```

Students do not simply copy the final Energy Meter project.

Instead, they first learn the individual building blocks and then combine them.

For example:

```text
LED
 ↓
GPIO
 ↓
Button
 ↓
Sensor
 ↓
ADC
 ↓
Voltage
 ↓
Current
 ↓
Power
 ↓
Energy
 ↓
Smart Energy Meter
```

This approach helps students understand how a complete engineering product is developed from smaller concepts.

---

# 🎯 Target Users

This educational kit is suitable for:

* School students
* Engineering students
* STEM laboratories
* Embedded systems beginners
* RISC-V beginners
* Electronics enthusiasts
* Robotics students
* IoT learners
* Innovation labs
* Educational institutions
* Embedded systems training programs

The learning path is designed to accommodate beginners while providing a foundation for advanced projects.

---

# 🌱 Future Scope

The platform can be expanded with additional modules and applications.

Possible future projects include:

* IoT Energy Monitoring
* Wireless Energy Dashboard
* Energy Data Logging
* Cloud Monitoring
* Environmental Monitoring
* Motor Control
* Robotics
* Battery Monitoring
* EV Systems
* Solar Energy Monitoring
* Smart Home Applications
* Industrial Monitoring
* Edge Computing

---

# 📸 Project Gallery

## Custom Educational PCB

*Add PCB image here.*

## VSDSquadron Ultra + Custom PCB

*Add hardware image here.*

## LED Experiment

*Add experiment image here.*

## Sensor Experiment

*Add sensor experiment image here.*

## Energy Meter

*Add final Energy Meter image here.*

## Student Learning

*Add student activity image here.*

---

# 🎥 Demonstration

*Add project demonstration video link here.*

Example:

```text
[Watch the Project Demonstration](YOUR_VIDEO_LINK)
```

---

# 📊 Project Status

| Component                     | Status            |
| ----------------------------- | ----------------- |
| VSDSquadron Ultra Integration | ✅ Completed       |
| Custom Educational PCB        | ✅ Completed       |
| LED Experiments               | ✅ Completed       |
| GPIO Experiments              | 🔄 In Development |
| Sensor Experiments            | 🔄 In Development |
| ADC Experiments               | 🔄 In Development |
| Voltage Measurement           | 🔄 In Development |
| Current Measurement           | 🔄 In Development |
| Energy Measurement            | 🔄 In Development |
| Smart Energy Meter            | 🔄 In Development |
| Student Documentation         | 🔄 In Development |

---

# 🤝 Contributions

Suggestions, improvements, experiments and educational content are welcome.

Students, educators, developers and RISC-V enthusiasts can contribute by:

* Adding new experiments
* Improving documentation
* Creating example programs
* Testing hardware
* Reporting issues
* Suggesting new educational applications

---

# ⚠️ Safety Notice

The Energy Meter section involves electrical measurements.

Students should perform electrical experiments only under proper supervision and with appropriate isolation, protection and safety procedures.

Do not directly connect unsafe mains voltage to the development board or custom PCB.

Always follow the electrical ratings and safety requirements of the measurement circuit.

---

# 📜 License

This repository may contain:

* Firmware
* Hardware designs
* PCB files
* Schematics
* Documentation
* Educational material

Appropriate licenses for hardware, software and documentation will be specified in the respective directories.

---

# ⭐ Project Vision

The goal of this project is simple:

> **Start with a single LED. End with a real engineering system.**

Students begin by learning basic electronics and programming.

They then learn how to interface sensors, process data and work with analog signals.

Finally, they combine everything to create a practical **Smart Energy Meter** using a RISC-V based platform.

```text
LEARN ELECTRONICS
       ↓
LEARN PROGRAMMING
       ↓
LEARN RISC-V
       ↓
BUILD CIRCUITS
       ↓
INTERFACE SENSORS
       ↓
PROCESS REAL DATA
       ↓
BUILD A REAL PRODUCT
```

---

# 🔗 References

* VSDSquadron Ultra
  https://www.vlsisystemdesign.com/vsdsquadronultra/

* VSDSquadron GitHub
  https://github.com/VSDSquadron

---

## Made for Hands-On RISC-V Learning

**VSDSquadron Ultra Educational Kit**

**From First LED → To Smart Energy Meter ⚡**
