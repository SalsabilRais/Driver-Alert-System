# 🚨 Multimodal Driver Safety & Alert System

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" alt="OpenCV" />
  <img src="https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=Arduino&logoColor=white" alt="Arduino" />
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white" alt="C++" />
  <img src="https://img.shields.io/badge/Serial_UART-4B5563?style=for-the-badge" alt="Serial UART" />
</p>

## 📌 Overview
A real-time **Driver Monitoring & Multimodal Alert System** combining **Computer Vision** and **Embedded Hardware**. The system analyzes live webcam footage to detect driver distraction (such as smartphone usage) or fatigue, and immediately triggers synchronized visual and acoustic warnings via an Arduino microcontroller.

---

## 🎯 Key Objectives
- **Real-Time Behavioral Analysis:** Continuously monitor the driver using computer vision algorithms.
- **Distraction Detection:** Identify unsafe behaviors (e.g., phone usage while driving) and trigger an on-screen `STATUS: ALERT!` warning.
- **Multimodal Hardware Feedback:** Bridge software detection with physical actuators (LEDs + Buzzer) for immediate driver reaction.

---

## ⚙️ System Architecture & Workflow

```text
[ Webcam Feed ] ──► [ Python + OpenCV Detection ] ──► ( Serial / UART ) ──► [ Arduino ] ──► [ Visual (LED) + Audio (Buzzer) ]
