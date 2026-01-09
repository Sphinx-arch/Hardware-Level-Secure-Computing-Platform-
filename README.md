# 🔐 Hardware-Level Secure Computing Platform  
**Author: Piyush Bansal**

This project converts a normal laptop into a **high-security, privacy-focused research machine** by modifying it at the **hardware level** and running a **secure live operating system (Tails OS)**.

Instead of trusting software alone, this setup removes built-in surveillance and persistence directly from the device.

---

## 🎯 Purpose

The goal was to:
- Understand **hardware-level security**
- Eliminate **camera, mic, and storage based spying**
- Build a **safe environment** for
  - Dark web research
  - Malware analysis
  - OSINT & threat intelligence

---

## 🔧 What I did

### 1. Removed internal storage
- Hard disk / SSD was physically removed  
- No data can be saved  
- Malware cannot persist  

📷 *Insert image: HDD removed*

---

### 2. Disabled camera and microphone
- Webcam cable disconnected  
- Microphone cable disconnected  
- Cannot be re-enabled by software or malware  

📷 *Insert image: Camera & mic cables removed*

---

### 3. Booted only from Tails OS
- System boots from USB  
- Runs fully in RAM  
- Uses Tor for all internet  
- Erases all data on shutdown  

📷 *Insert image: Tails OS boot*

---

## 🔐 Security Features

- No camera  
- No microphone  
- No hard drive  
- Tor-only networking  
- No data persistence  
- Resistant to malware & tracking  

This creates a **secure, anonymous cyber-research workstation**.

---

## 🚀 Future Plan

Next phase:
- Remove Intel Management Engine  
- Install Coreboot / Libreboot  
- Build custom secure BIOS  

Goal:  
> Full control from hardware → firmware → OS

---

## 🧠 Why this project matters

This is not just a software setup.  
It demonstrates:
- Hardware security
- Threat modeling
- Privacy engineering
- Real-world cybersecurity thinking  

This is how secure systems are built in high-trust environments.
