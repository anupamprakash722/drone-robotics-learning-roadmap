# 🚁 Drone Robotics Learning Roadmap

> *A structured, project-based journey from mathematical foundations to autonomous drone flight — documenting my PhD learning process at the [Center for AI and Robotics](your-lab-url).*

[![GitHub stars](https://img.shields.io/github/stars/YOUR_USERNAME/drone-robotics-learning-roadmap?style=social)](https://github.com/YOUR_USERNAME/drone-robotics-learning-roadmap)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)
![ROS2](https://img.shields.io/badge/ROS2-Humble-orange.svg)
![Status](https://img.shields.io/badge/Status-In%20Progress-brightgreen.svg)

---

## 📖 About This Repository

This is a **meta-repository** — it contains no code itself. Instead, it serves as the **central navigation hub** for my entire drone robotics portfolio. 

Each linked project is a self-contained repository that builds upon the previous one, forming a coherent learning arc from raw mathematics to a fully autonomous simulated drone.

**Why this exists:**
- 📂 Provides a single entry point to all my drone robotics work
- 🗺️ Shows the pedagogical sequence and how concepts interconnect
- 🎯 Demonstrates structured, intentional learning to potential collaborators and employers
- 📝 Documents my growth during my PhD at the Center for AI and Robotics

---

## 🗺️ Learning Path Overview

```mermaid
graph TD
    A[1. Math Foundations] --> B[2. PID Control 1D]
    B --> C[3. LQR Control 2D]
    C --> D[4. Kalman Filter EKF]
    D --> E[5. 3D Full Simulation]
    E --> F[6. Trajectory Optimization]
    F --> G[7. ROS2 + Gazebo]
    
    A -.-> H[Intuition & Tools]
    B -.-> I[Classical Control]
    C -.-> J[Modern Control]
    D -.-> K[State Estimation]
    E -.-> L[Systems Integration]
    F -.-> M[Planning]
    G -.-> N[Real-World Deployment]
