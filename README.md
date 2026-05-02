# Tensor-0 | Robotics & Embodied AI

<p align="center">
  <img src="https://img.shields.io/badge/Bipedal_Humanoid-RL_Locomotion-blue?style=for-the-badge&logo=ai" alt="Bipedal RL">
  <img src="https://img.shields.io/badge/RoboMaster-Full_Stack-E95420?style=for-the-badge&logo=robot" alt="RoboMaster">
  <img src="https://img.shields.io/badge/Ubuntu_22.04-Developer-E95420?style=for-the-badge&logo=ubuntu" alt="Ubuntu">
</p>

---

## 🇨🇳 简体中文版本

### 个人简介

你好，我是 **张量 (Tensor-0)**。

目前研究方向为**具身人工智能（Embodied AI）**，具体包括**足式机器人的强化学习 (RL) Locomotion** 算法及其物理实体部署。

工程实践中，将运动学闭链解算、LQR/VMC 等数学方法与 AI 算法结合，应用于双足平台与高机动底盘的运动控制。

> 欢迎与科研团队及开源同行交流与合作。

### 核心项目

#### RooCode Plus — 多模型本地代理适配层

针对 Roo Code 的多模型本地代理适配层。基于 FastAPI 构建本地服务拦截与重构 HTTP 请求，动态注入缺失参数，解决 Roo Code 与 DeepSeek 等模型间的 API 格式不兼容及上下文截断问题。包含跨平台自动化安装与测试脚本。

`Python` `FastAPI` `Shell`

---

#### DBRL — 达妙双足机器人强化学习框架

针对达妙 19 自由度双足机器人的 RL 步态优化框架，包含 Isaac Gym 仿真环境搭建、策略训练，以及 ONNX 模型在物理硬件上的 Sim-to-Real 部署。

`强化学习 (RL)` `双足机器人` `具身智能`

> [GitHub](https://github.com/Tensor-0/dbrl-damiao-bipedal-rl)

#### BPIC — 偏置并联步兵底盘控制器

针对 RoboMaster 偏置并联机构的 C++ 底层控制框架，实现了闭链运动学正逆解算器与基于 LQR/VMC 的倒立摆平衡控制器。

`C/C++` `运动学与动力学` `平衡控制`

> [GitHub](https://github.com/Tensor-0/rm-biased-parallel-controller)

#### FDC — 摩擦轮飞镖发射控制系统

摩擦轮飞镖发射时序与转速控制器，通过 PID/ADRC 实现双电机同步闭环，以有限状态机 (FSM) 管理发射流程。

`STM32` `控制算法` `状态机`

> [GitHub](https://github.com/Tensor-0/friction-dart-controller)

#### GMFS — 黄金矿工全栈机器人方案

自主检索机器人系统，集成了 OpenCV 视觉检测、机械臂抓取控制与底盘驱动。

`全栈开发` `机器视觉`

> [GitHub](https://github.com/Tensor-0/goldminer-robot-fullstack)

### 📝 LocoWiki — 个人开发日志库

我的技术日志库，用于沉淀每日开发复盘、错误排查记录以及机器人数理推导。

- [开启今日复盘](https://github.com/Tensor-0/LocoWiki/discussions/new?category=💡-每日复盘与碎碎念)
- [🐧 Linux 踩坑录](https://github.com/Tensor-0/LocoWiki/discussions/categories/linux-踩坑录)
- [🧮 RL 理论推导](https://github.com/Tensor-0/LocoWiki/discussions/categories/rl-与控制理论推导)

---

## 🌍 English Version

### Profile

I study Robotics Engineering with a focus on **Embodied AI**. My work covers high-speed combat robotic systems and high-DOF bipedal locomotion, with current emphasis on **Reinforcement Learning (RL)** for sim-to-real transfer of articulated robots and robust dynamic gait generation.

> Open to collaborations on open-source robotics, RL algorithms, and related technical work.

### Featured Projects

#### RooCode Plus — Multi-Model Local Proxy Adapter

A local proxy adapter for Roo Code, built on FastAPI to intercept and restructure HTTP requests. Dynamically injects missing fields to resolve API format incompatibilities and context truncation between Roo Code and models like DeepSeek. Includes cross-platform automation scripts for installation and testing.

`Python` `FastAPI` `REST API`

---

#### DBRL — Damiao Bipedal Reinforcement Locomotion

RL-based gait optimization framework for the Damiao 19-DOF bipedal humanoid robot. Covers Sim-to-Real deployment and high-DOF policy control on NVIDIA Orin platforms.

`Reinforcement Learning` `Isaac Gym` `Sim-to-Real`

> [GitHub](https://github.com/Tensor-0/dbrl-damiao-bipedal-rl)

#### BPIC — Biased Parallel Infantry Controller

C++ motion control framework for RoboMaster biased parallel infantry chassis. Implements non-linear kinematics solvers and LQR/VMC balance control.

`C++` `Kinematics` `LQR/VMC`

> [GitHub](https://github.com/Tensor-0/rm-biased-parallel-controller)

#### FDC — Friction Dart Controller

Launch sequence controller for friction-wheel dart systems, with dual-motor speed synchronization (PID/ADRC) and finite-state-machine sequencing.

`Control Theory` `Embedded Systems`

> [GitHub](https://github.com/Tensor-0/friction-dart-controller)

#### GMFS — GoldMiner Full-Stack

Full-stack autonomous retrieval system integrating OpenCV-based object detection with STM32 chassis control.

`STM32` `Computer Vision` `Full-Stack`

> [GitHub](https://github.com/Tensor-0/goldminer-robot-fullstack)

### 📝 LocoWiki — Developer Log

A workspace for daily research logs, debugging notes, and math derivations for embodied AI.

- [Write a Daily Log](https://github.com/Tensor-0/LocoWiki/discussions/new?category=💡-每日复盘与碎碎念)
- [🐧 Linux Error Logs](https://github.com/Tensor-0/LocoWiki/discussions/categories/linux-踩坑录)
- [🧮 RL & Math Derivations](https://github.com/Tensor-0/LocoWiki/discussions/categories/rl-与控制理论推导)

---

## 🛠️ 技术储备 / Technical Stack

### 算法与仿真 (AI & Simulation)

![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![Isaac Gym](https://img.shields.io/badge/Isaac_Gym-76B900?style=for-the-badge&logo=nvidia&logoColor=white)
![MuJoCo](https://img.shields.io/badge/MuJoCo-000000?style=for-the-badge&logo=openai&logoColor=white)
![ROS2](https://img.shields.io/badge/ROS2-22314E?style=for-the-badge&logo=ros&logoColor=white)

### 软件与硬件 (Software & Hardware)

![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Ubuntu](https://img.shields.io/badge/Linux_Ubuntu-E95420?style=for-the-badge&logo=ubuntu&logoColor=white)
![STM32/Orin](https://img.shields.io/badge/STM32_/_Orin-76B900?style=for-the-badge&logo=nvidia&logoColor=white)

---

## 🤝 联系方式 / Connect with Me

[![Email](https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:3247167757@qq.com)
[![Bilibili](https://img.shields.io/badge/Bilibili-00A1D6?style=for-the-badge&logo=bilibili&logoColor=white)](https://space.bilibili.com/171912855)
[![Zhihu](https://img.shields.io/badge/Zhihu-0084FF?style=for-the-badge&logo=zhihu&logoColor=white)](https://www.zhihu.com/people/70-53-83-52-49)

---

<p align="center">
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Tensor-0&theme=radical&hide_border=true" alt="GitHub Streak">
</p>

<p align="center"><em>"Iterating on the future of embodied locomotion, one tensor at a time."</em></p>
