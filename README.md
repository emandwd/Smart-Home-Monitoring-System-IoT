# Smart Home Monitoring System

## Overview
This project implements a comprehensive IoT home monitoring solution designed to enhance automation, comfort, and security. The system consists of three main modules:

### Lighting Control
Automatic motion-triggered lighting using a microwave radar sensor, along with voice-controlled brightness adjustment through ESP32 and Amazon Alexa.

### Temperature Control
Environmental monitoring using DHT22 sensors to manage heating and cooling systems automatically or through cloud-based control.

### AI Smart Door Lock
A high-security access control system that includes:
- Facial recognition using NVIDIA Jetson Nano
- Fingerprint authentication
- Remote monitoring and control via a mobile dashboard

---

## Hardware Components
- ESP32 Microcontroller  
- NVIDIA Jetson Nano  
- HLK-LD2412 Microwave Radar Motion Sensor  
- DHT22 Temperature & Humidity Sensor  
- R307 Optical Fingerprint Sensor  
- Raspberry Pi Camera Module V2  
- 12V Solenoid Door Lock  

---

## Technical Standards and Communication
- Wi-Fi: IEEE 802.11 b/g/n  
- Video Streaming: RTSP (Real-Time Streaming Protocol)  
- Cloud Communication: REST APIs and WebSockets  

---

## Security
- Data in Transit: TLS 1.2 / TLS 1.3  
- Data at Rest: AES-256 Encryption  
- Authentication: OAuth 2.0  

---

## Cloud Services
- Supabase: Persistent data storage  
- Firebase: Real-time notifications  

---

## Features
- Motion-based smart lighting with voice control  
- Automated temperature sensing and regulation  
- Multi-factor door access system (face + fingerprint)  
- Remote monitoring and real-time updates via cloud  

---
