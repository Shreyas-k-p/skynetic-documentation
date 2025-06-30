# 🚀 Skynetic – Where Machines Feel

<div align="center">
<div style="background-color: #000; padding: 20px; border-radius: 12px; display: inline-block;">
  <img src="./logo.jpg" alt="Ecocee Logo" width="120" height="120" />
</div>

### Internship Project at [Ecocee](https://ecocee.in)

[![Website](https://img.shields.io/badge/Website-ecocee.in-blue?style=for-the-badge&logo=globe)](https://ecocee.in)
[![Email](https://img.shields.io/badge/Contact-info%40ecocee.in-red?style=for-the-badge&logo=gmail)](mailto:info@ecocee.in)
</div>

---

## 📋 Project Overview

**Batch:** Summer 2025  
**Team Number:** Team #03  
**Internship Position:** Embedded Developer Intern  
**Duration:** 12 June – 30 June 2025 (15 Days)

### 👥 Team Members
| Name | Role | Email | LinkedIn |
|------|------|-------|----------|
| Shreyas K P | Developer | shreyas5710kp@gmail.com | [LinkedIn](https://www.linkedin.com/in/shreyas-k-p-5016a432b) |
| Amrithraj M M | Developer | amruthrajmurali1441@gmail.com | [LinkedIn](https://www.linkedin.com/in/amrithraj-m-m-512780338) |

---

## 🎯 Description

**Skynetic** is a robotic sensing project where ESP32-S2-WROVER is used to identify physical interactions with a robot — distinguishing between soft touches and harsh slaps. Flex sensors and MS5837 pressure sensors detect and measure the force, while LEDs provide immediate feedback. This project bridges human emotion with machine perception.

---

## 🔧 Technical Specifications

### Embedded Developer Project:
- **Microcontroller:** ESP32-S2-WROVER
- **Programming Language:** C++ (Arduino)
- **Communication:** I2C (for pressure sensor), analog (flex sensor), digital output (LEDs)
- **Sensors/Components:** MS5837 Pressure Sensor, Flex Sensors, 74HC4051 Multiplexer, LEDs, Resistors
- **IDE:** Arduino IDE

---

## ⚙️ Project Working

### Architecture Overview
- Human interaction → Sensor detection → Signal processing → Decision → LED indication

### Key Components
1. **Flex Sensor:** Detects bending
2. **MS5837 Pressure Sensor:** Measures pressure in mbar
3. **ESP32:** Microcontroller that processes input and controls LEDs

### Algorithm/Logic Flow
```
Step 1: Initialize all sensors and LEDs
↓
Step 2: Continuously read data from pressure and flex sensors
↓
Step 3: If flex is bent and pressure is high → Slap detected
↓
Step 4: If flex is bent and pressure is low → Touch detected
↓
Step 5: Output to respective LED
```

---

## 🚀 Applications & Use Cases

### Primary Applications
- Enhancing **Human-Robot Interaction (HRI)**
- Wearable **assistive technologies**
- **Security bots** that respond to aggressive behavior

### Future Scope
- Add vibration or haptic feedback
- Wireless communication via WiFi/Bluetooth
- Real-time data visualization
- Gesture classification using ML

---

## 📱 Demo & Results

### Screenshots/Images
> [To be updated upon circuit test and result documentation](https://github.com/Shreyas-k-p/Skynetic/blob/main/Screenshot%202025-06-28%20011825.png)

### Performance Metrics
| Metric | Value |
|--------|-------|
| Flex Detection Threshold | ~1800 |
| Pressure Range | 300–1000+ mbar |
| Reaction Time | ~200 ms |

---

## 🛠️ Installation & Setup

### Prerequisites
```bash
- Arduino IDE
- ESP32 Board installed
- Required Libraries: Wire.h
```

### Installation Steps
```bash
git clone https://github.com/Shreyas-k-p/Skynetic.git
cd Skynetic
Open .ino file in Arduino IDE
Upload to ESP32-S2-WROVER
```

### Usage
```bash
Connect sensors to ESP32
Power the system
Touch or slap to see LED response
```

---

## 📊 Project Structure
```
Skynetic/
├── code/                 # Arduino IDE code
├── docs/                 # Block & Circuit Diagrams
├── presentation/         # PPT
├── README.md             # Overview and Summary
```

---

## 🎓 Learning Outcomes

### Technical Skills Gained
- Embedded system design
- Sensor interfacing
- Real-time signal processing

### Tools & Technologies Mastered
- ESP32-S2-WROVER
- Arduino IDE
- Git & GitHub
- Sensor calibration & multiplexing

---

## 🤝 Acknowledgments

Thank you **Ecocee** for this internship opportunity and technical guidance throughout the embedded training.

**Mentor:** Sreeraj V Rajesh  
**Team Number:** 03  
**Team Size:** 2 Members

### 👨‍💼 Team Contributions
| Team Member | Primary Contributions |
|-------------|------------------------|
| Shreyas K P | Coding, Circuit Design, Documentation, Presentation|
| Amrithraj M M | Component Wiring, Testing, Presentation, Documentation |

---

## 📞 Contact

**Company:** Ecocee  
**Website:** [ecocee.in](https://ecocee.in)  
**Email:** [info@ecocee.in](mailto:info@ecocee.in)

### 👥 Team Contacts
| Team Member | Email | LinkedIn | GitHub |
|-------------|-------|----------|--------|
| Shreyas K P | shreyas5710kp@gmail.com | [LinkedIn](https://www.linkedin.com/in/shreyas-k-p-5016a432b) | [GitHub](https://github.com/Shreyas-k-p) |
| Amrithraj M M | amruthrajmurali1441@gmail.com | [LinkedIn](https://www.linkedin.com/in/amrithraj-m-m-512780338) | [GitHub](https://github.com/AMRITHRAJ2002) |

---

<div align="center">

**Made with ❤️ during internship at Ecocee**

⭐ **Star this repo if you found it helpful!** ⭐

</div>

---

## 📄 License

This project is developed as part of an internship program at Ecocee. Please contact the company for usage and distribution rights.

[Optional: Add specific license if applicable]
