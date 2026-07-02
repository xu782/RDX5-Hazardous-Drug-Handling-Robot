# 🧪 基于 RDK X5 与 ROS 2 的自主药品搬运与分类回收系统

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![ROS 2](https://img.shields.io/badge/ROS%202-Humble-blue)](https://docs.ros.org/en/humble/)
[![Platform](https://img.shields.io/badge/Platform-RDK%20X5-brightgreen)](https://www.horizon.ai/)
[![Status](https://img.shields.io/badge/Status-Developing-yellow)]()

---

## 📌 项目简介

本项目面向**工厂、实验室、仓库**等场景中的**药品搬运与分类回收**需求，旨在解决人工操作中**气体泄漏、化学品灼伤**等安全隐患。

系统以 **RDK X5** 为核心算力单元（"大脑"），**STM32F103** 负责底盘运动控制（电机驱动与里程计采集），**STM32H743** 负责机械臂关节控制与抓取执行，形成 **"大脑 + 双小脑"** 的上下位机架构。内置激光雷达、视觉模块、气体传感模块、IMU 惯导、机械臂及声光报警器，构建了一套具备环境安全监测能力的全自主 **"感知—决策—执行"** 任务闭环。

> ⚠️ **当前进度说明**：激光 SLAM **建图功能已完成**，路径规划与自主导航功能正在开发中，其余模块（YOLO 视觉识别、气体传感、机械臂控制、云端上报等）均已基本完成。

---

## 🎯 应用场景

| 场景 | 典型任务 |
|:---|:---|
| 🏭 工厂 | 危险化学品搬运、分类回收 |
| 🧪 实验室 | 实验药品取用、废液回收 |
| 📦 仓库 | 智能物料拣选、库存管理 |

---

## 🏗️ 系统架构
