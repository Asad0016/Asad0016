# 👋 ASAD ULLAH: EMBEDDED FIRMWARE ENGINEER

> *"Never Give Up"* 😎
---

<p align="center">
  <img src="360_F_460636484_5KLRqy4CgptG7Bt4S1nY80v7tPm3e5Tm.jpg" alt="My Image">
</p>


---

Welcome to my GitHub profile! I specialize in embedded systems and firmware development, combining hardware and software to create intelligent, connected solutions. Whether it's IoT devices, wireless communication, or real-time embedded applications — this is where innovation happens.



## 🔧 About Me

- 🎯 **Embedded Systems Developer**  
   Experienced with microcontrollers like **ESP32**, **STM32**, and **AVR**, focused on writing efficient low-level firmware for real-time systems.

- 📡 **IoT Integrator**  
   Skilled in wireless communication technologies such as **BLE**, **ESP-NOW**, **Zigbee**, and **MQTT**, enabling smart device connectivity.

- 🌐 **Cloud-Connected Solutions**  
   Proficient in integrating cloud platforms like **AWS IoT** and **Google Cloud** for remote monitoring and control.

- 🛠 **Problem Solver**  
   Passionate about debugging, optimizing performance, and pushing hardware to its limits.

---

## 💻 Skills & Technologies

### 🖥️ Languages
<p>
  <img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white"/>
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/QML-41CD52?style=for-the-badge&logo=qt&logoColor=white"/>
</p>

### 🔌 Microcontroller / Compute Modules
<p>
  <img src="https://img.shields.io/badge/STM32-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white"/>
  <img src="https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white"/>
  <img src="https://img.shields.io/badge/NRF52-00A9CE?style=for-the-badge&logoColor=white"/>
  <img src="https://img.shields.io/badge/8051-grey?style=for-the-badge&logoColor=white"/>
  <img src="https://img.shields.io/badge/Raspberry%20Pi-A22846?style=for-the-badge&logo=raspberrypi&logoColor=white"/>
  <img src="https://img.shields.io/badge/NVIDIA-76B900?style=for-the-badge&logo=nvidia&logoColor=white"/>
</p>

### 📡 Protocols — Wireless
<p>
  <img src="https://img.shields.io/badge/Bluetooth-0082FC?style=for-the-badge&logo=bluetooth&logoColor=white"/>
  <img src="https://img.shields.io/badge/LoRa-24A1C1?style=for-the-badge&logoColor=white"/>
  <img src="https://img.shields.io/badge/ESP--NOW-E7352C?style=for-the-badge&logo=espressif&logoColor=white"/>
  <img src="https://img.shields.io/badge/MQTT-660066?style=for-the-badge&logo=mqtt&logoColor=white"/>
  <img src="https://img.shields.io/badge/Zigbee-EB0443?style=for-the-badge&logoColor=white"/>
  <img src="https://img.shields.io/badge/Modbus-grey?style=for-the-badge&logoColor=white"/>
  <img src="https://img.shields.io/badge/FreeRTOS-8CC84B?style=for-the-badge&logoColor=white"/>
</p>

### 🛠️ IDEs / Code Editors / Frameworks
<p>
  <img src="https://img.shields.io/badge/PlatformIO-FF6600?style=for-the-badge&logo=platformio&logoColor=white"/>
  <img src="https://img.shields.io/badge/Qt%20Creator-41CD52?style=for-the-badge&logo=qt&logoColor=white"/>
  <img src="https://img.shields.io/badge/VS%20Code-007ACC?style=for-the-badge&logo=visualstudiocode&logoColor=white"/>
  <img src="https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white"/>
  <img src="https://img.shields.io/badge/Keil-1B6AC6?style=for-the-badge&logoColor=white"/>
  <img src="https://img.shields.io/badge/STM32CubeIDE-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white"/>
  <img src="https://img.shields.io/badge/MPLAB-DD1100?style=for-the-badge&logoColor=white"/>
  <img src="https://img.shields.io/badge/NRF%20Connect-00A9CE?style=for-the-badge&logoColor=white"/>
</p>

### ☁️ Clouds
<p>
  <img src="https://img.shields.io/badge/AWS%20IoT-232F3E?style=for-the-badge&logo=amazonaws&logoColor=white"/>
  <img src="https://img.shields.io/badge/Google%20Cloud-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white"/>
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black"/>
</p>

### 🧰 Tools
<p>
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white"/>
  <img src="https://img.shields.io/badge/GitLab-FC6D26?style=for-the-badge&logo=gitlab&logoColor=white"/>
  <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white"/>
  <img src="https://img.shields.io/badge/Jenkins-D24939?style=for-the-badge&logo=jenkins&logoColor=white"/>
</p>

---

# 📁 Projects



## 🔌 Zigbee-Based Wireless Monitoring System (ESP32-C6)

In this project, I developed a wireless data communication system using **Zigbee protocol** between a **Coordinator (Server)** and a **Router (Client)**.

### 📡 Project Overview:

- **Router (Client)**:
  - Acts as a **Zigbee Router** using `ESP32-C6` with the **ESP-IDF framework**.
  - Collects real-time current readings using a **Current Transformer (CT Sensor)**.
  - Sends the sensor data wirelessly to the Coordinator.

- **Coordinator (Server)**:
  - Also based on `ESP32-C6` configured as a **Zigbee Coordinator**.
  - Receives the current readings from the router node.
  - Can be expanded to log data, visualize trends, or trigger actions.

### ⚙️ Technologies Used:
- **ESP32-C6** (with Zigbee support)
- **ESP-IDF** (Espressif IoT Development Framework)
- **Zigbee Protocol**
- **Current Transformer (CT) Sensor**
- **UART & Wireless Communication**

> 📌 *This project demonstrates wireless sensor communication using Zigbee for applications like smart metering, energy monitoring, and home automation.*

[//]: # (Code not shared publicly for confidentiality. You can contact me to discuss the implementation.)

---
# BLE and ESP-NOW Based Wireless Audio Communication

This project showcases a **real-time wireless audio communication system** using **ESP32-S3 microcontrollers**, leveraging **custom BLE services** and the **ESP-NOW protocol**.

## 🧠 Project Overview

A custom **Bluetooth Low Energy (BLE)** service was developed on the ESP32-S3 and interfaced with the **nRF Connect mobile application**. Using this app, specific commands were sent to the ESP32. The key command, **"Start Communication"**, triggered wireless audio streaming functionality.

Once activated:

- The **server-side ESP32-S3**, connected to a **microphone**, captured audio samples.
- Audio data was packed into buffers and transmitted wirelessly using **ESP-NOW** to the **client-side ESP32-S3**.
- The **client ESP32** decoded the received audio buffers and played them in real-time using an **audio amplifier**.

This approach repurposes **ESP-NOW**, typically used for control signals, to handle **real-time audio streaming**, which is both bandwidth-intensive and time-sensitive.

## 🚀 Features

- ✅ **Custom BLE service** with command-based control
- 📶 **Real-time wireless audio streaming** using ESP-NOW
- 🎙️ **Microphone-based audio capture**
- 🔊 **Audio playback through amplifier**
- ⚙️ Developed using **ESP-IDF** for bare-metal firmware control

## 🔧 Technologies Used

- **ESP32-S3**
- **ESP-IDF**
- **nRF Connect (mobile BLE app)**
- **BLE (Bluetooth Low Energy)**
- **ESP-NOW protocol**

## 📂 Repository Structure

> _Note: Code is not included here. This repository serves as a project showcase._
