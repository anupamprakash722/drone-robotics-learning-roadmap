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

    
---

## 🛠️ Technology Stack

| Category | Technologies |
|:---|:---|
| **Language** | Python 3.8+, C++ (ROS2 nodes) |
| **Mathematics** | NumPy, SciPy, SymPy |
| **Control** | python-control, custom implementations |
| **Optimization** | CVXPY, SciPy optimize |
| **Visualization** | Matplotlib, Plotly |
| **Middleware** | ROS2 Humble, Gazebo |
| **Containerization** | Docker |
| **Testing** | pytest, unittest |

---

## 🎯 Learning Philosophy

I'm a Computer Science engineer by training (B.Tech + M.Tech in CSE) pursuing a PhD in AI and Robotics with a focus on drones. Mathematics and physics didn't come naturally to me — this roadmap documents my deliberate practice approach:

1. **Code first, derive later** — implement concepts computationally to build intuition
2. **One concept per project** — avoid cognitive overload
3. **Simulate before flying** — master algorithms in Python before touching hardware
4. **Document everything** — each repo has detailed READMEs with theory, equations, and results
5. **Build in public** — share the journey, not just the destination

---

## 📊 My Research Context

- **PhD Institution:** IIT Mandi
- **Research Center:** Center for AI and Robotics
- **Research Area:** Aerial Robotics / Drone Autonomy
- **Research Focus:** [Brief description — e.g., "Autonomous navigation in GPS-denied environments" or "Reinforcement learning for aggressive drone maneuvers"]

---

## 🚀 How to Use This Roadmap

### For Learners
If you're on a similar journey, follow the projects in numbered order. Each repository has:
- 📖 Detailed README with theory
- 💻 Runnable code with clear instructions
- 🧪 Unit tests verifying correctness
- 📓 Jupyter notebooks for exploration

### For Potential Collaborators
Issues and feature requests are welcome on individual project repositories. If you find this roadmap valuable, consider ⭐ starring the repos.

### For Recruiters / Professors
This portfolio demonstrates proficiency in:
- Mathematical modeling of dynamic systems
- Classical and modern control theory
- Probabilistic state estimation
- Trajectory planning and optimization
- Robot Operating System (ROS2)
- Software engineering practices (testing, documentation, CI/CD)

---

## 📬 Contact

- **GitHub:** [@YOUR_USERNAME](https://github.com/[YOUR_USERNAME])
- **LinkedIn:** [Your LinkedIn URL]
- **Email:** [your.email@example.com]
- **Google Scholar:** [Your Scholar URL, if applicable]

---

---

<p align="center">
  <i>Built with ☕ and determination during my PhD journey.</i>
</p>
