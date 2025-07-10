# 🌍 Landslide Prediction IoT System (Node-RED + Firebase)

A **low-cost, real-time IoT framework** for landslide prediction and risk communication, based on concepts from the book *A to Z IoT*.  
This project uses **Node-RED**, **Firebase**, and simulated sensor data to detect early signs of landslides using **soil moisture** and **tilt angle thresholds**.

---

## 📽️ Project Presentation

▶️ View the full presentation here:  
[📎 IoT Node-RED Landslide Monitoring (PowerPoint)](https://1drv.ms/p/c/bda4c2e60bdc1ec4/EaLIgU7z_tlOqpyAOBIk9D0BOWvk8NAxicsOJ9vBkxJn8A?e=rNW6ix)

---

## 🚀 Features

- 📡 Simulated sensor input (moisture + tilt)
- 🧠 Threshold logic using Node-RED function nodes
- 📊 Interactive dashboard (gauges + line charts)
- ☁️ Firebase Realtime Database integration (via HTTP)
- 🔔 Visual alert system for landslide risk

---

## 🛠️ Project Structure
📁 Node-RED Flow
├── Simulated Sensor Input
├── Threshold Checker (moisture > 60%, tilt > 15°)
├── Firebase HTTP POST
├── Dashboard: Text, Gauges, Charts


---

## 📦 Dependencies

Install the following Node-RED packages:

```bash
npm install node-red-dashboard
npm install node-red-contrib-firebase

