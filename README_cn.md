# 🧪 Autonomous Drug Handling & Sorting System Based on RDK X5 and ROS 2

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![ROS 2](https://img.shields.io/badge/ROS%202-Humble-blue)](https://docs.ros.org/en/humble/)
[![Platform](https://img.shields.io/badge/Platform-RDK%20X5-brightgreen)](https://www.horizon.ai/)
[![Status](https://img.shields.io/badge/Status-Developing-yellow)]()

---

## 📌 Introduction

This project addresses the need for **drug handling and sorting/recycling** in factories, laboratories, and warehouses, eliminating safety hazards such as **gas leaks and chemical burns** caused by manual operations.

The system uses **RDK X5** as the core computing unit (the "brain"), **STM32F103** for chassis motion control (motor driving and odometry), and **STM32H743** for robotic arm joint control and grasping execution – forming a **"brain + dual cerebellum"** upper-lower computer architecture. It integrates LiDAR, a vision module, gas sensors, an IMU, a robotic arm, and an audible/visual alarm, building a fully autonomous **"perception–decision–execution"** closed loop with environmental safety monitoring.

> ⚠️ **Current Progress**: Laser SLAM **mapping is completed**; path planning and autonomous navigation are **under development**. All other modules (YOLO vision, gas sensing, arm control, cloud reporting, etc.) are largely finished.

---

## 🎯 Application Scenarios

| Scenario | Typical Tasks |
|:---|:---|
| 🏭 Factory | Transport and sort hazardous chemicals |
| 🧪 Laboratory | Retrieve experimental drugs and recycle waste liquids |
| 📦 Warehouse | Intelligent material picking and inventory management |

---

## 🏗️ System Architecture
