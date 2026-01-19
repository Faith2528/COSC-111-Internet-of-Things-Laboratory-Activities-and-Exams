# 🎓 Student Portfolio in COSC 111

![Course](https://img.shields.io/badge/Course-Internet_of_Things-181717?style=for-the-badge&logo=internetofthings&logoColor=white) ![Section](https://img.shields.io/badge/Section-BSCS_4C-blue?style=for-the-badge)

**Subject:** Internet of Things (IoT) Laboratory  
**Student Name:** Lhojen Faith C. Bonganay  
**Section:** BSCS - 4C  
**Instructor:** Johnroe Paulo Cañamaque 

---

## 📖 Portfolio Overview
This repository serves as a compilation of all laboratory activities, examinations, and prototypes developed for the **COSC 111** course. The projects range from basic digital signal processing on an Arduino to complex, bi-directional communication systems involving Python scripts and FastAPI web servers.

**Note:** Each folder contains the source code (`.ino`, `.py`) and a detailed documentation file explaining the circuit logic and implementation.

---

## 📂 Laboratory Activities

### [Laboratory Activity 1: Working with Digital Signals](./Laboratory%20Activity%20%231%3A%20Working%20with%20Digital%20Signals)
![Focus](https://img.shields.io/badge/Focus-Digital_Output-2ea44f?style=flat-square) ![Tech](https://img.shields.io/badge/Code-digitalWrite()-blue?style=flat-square)
* **📝 Description:** A foundational project implementing a "Running Light" circuit. It demonstrates the control of multiple LEDs in a sequential pattern using digital high/low signals.

### [Laboratory Activity 2: Working with Analog Signals](./Laboratory%20Activity%20%232%3A%20Working%20with%20Analog%20Signals)
![Focus](https://img.shields.io/badge/Focus-Analog_PWM-orange?style=flat-square) ![Tech](https://img.shields.io/badge/Code-analogWrite()-blue?style=flat-square)
* **📝 Description:** An evolution of the running light circuit that introduces analog signals. It controls the brightness of LEDs rather than just their on/off state, utilizing arrays and loops for efficient pin management.

### [Laboratory Activity 3: Working with Sensors](./Laboratory%20Activity%20%233%3A%20Working%20with%20Sensors)
![Focus](https://img.shields.io/badge/Focus-Sensors_&_Alarms-d9534f?style=flat-square) ![Tech](https://img.shields.io/badge/Hardware-Thermistor_%7C_LDR-gray?style=flat-square)
* **📝 Description:** A "Fire Sensor" prototype. This system reads real-time data from temperature and light sensors, triggering a visual alarm (flashing LED) when environmental readings exceed defined safety thresholds.

### [Laboratory Activity 4: Arduino Serial Connection](./Laboratory%20Activity%20%234%3A%20Arduino%20Serial%20Connection)
![Focus](https://img.shields.io/badge/Focus-UART_Communication-9b59b6?style=flat-square) ![Mode](https://img.shields.io/badge/Mode-Latching_Logic-yellow?style=flat-square)
* **📝 Description:** A remote-controlled sensor system. It sends sensor data to the Serial Monitor and allows the user to manually override alarms by typing text commands directly into the Arduino console.

### [Laboratory Activity 5: Receiving Serial Connection from Python](./Laboratory%20Activity%20%235%3A%20Receiving%20serial%20connection%20using%20Arduino%20from%20Python%20Objectives%3A)
![Focus](https://img.shields.io/badge/Integration-Python_Scripting-3776AB?style=flat-square&logo=python&logoColor=white) ![Lib](https://img.shields.io/badge/Lib-pySerial-green?style=flat-square)
* **📝 Description:** A software-hardware integration project. A Python script runs on the host computer, providing a terminal-based UI that allows the user to toggle specific LEDs on the Arduino board.

### [Laboratory Activity 6: Bidirectional Control](./Laboratory%20Activity%20%236%3A%20Bidirectional%20Control%20Using%20Arduino%20and%20Python)
![Focus](https://img.shields.io/badge/Architecture-Full_Duplex-FF6F00?style=flat-square) ![Flow](https://img.shields.io/badge/Flow-Arduino_%E2%86%94_Python-3776AB?style=flat-square)
* **📝 Description:** A complex feedback loop system. Pushing physical buttons on the Arduino sends signals to Python, which processes the request and sends commands back to the Arduino to control output LEDs, simulating a responsive IoT environment.

### [Laboratory Activity 7: Controlling Arduino using FastAPI](./Laboratory%20Activity%20%237%3A%20Controlling%20Arduino%20using%20FastAPI)
![Focus](https://img.shields.io/badge/Web_API-FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white) ![Protocol](https://img.shields.io/badge/Protocol-HTTP_Request-black?style=flat-square)
* **📝 Description:** Replaces the terminal interface with a modern web API. The Arduino hardware is controlled via HTTP endpoints (e.g., `/led/red`), bridging the gap between hardware serial ports and web technologies.

---

## 🏆 Examinations

### [Midterm Exam: Smart Lighting System](./Laboratory%20Midterms%20Exam)
![Type](https://img.shields.io/badge/Exam-Midterms-important?style=for-the-badge) ![System](https://img.shields.io/badge/System-Smart_Street_Light-yellow?style=flat-square)
* **📝 Description:** A smart system with "Manual" and "Automatic" modes. In Auto mode, it simulates weather conditions (Cloudy, Sunny) and adjusts LED indicators dynamically based on light intensity readings.

### [Final Exam: Arduino-to-Python API Client](./Laboratory%20Finals%20Exam)
![Type](https://img.shields.io/badge/Exam-Finals-success?style=for-the-badge) ![Concept](https://img.shields.io/badge/Concept-Physical_API_Client-blueviolet?style=flat-square)
* **📝 Description:** A "Physical Client" system where the Arduino acts as a tactile trigger. Pressing a button on the hardware signals a Python script to perform a real HTTP request to a remote API server, demonstrating the decoupling of hardware input from network logic.
