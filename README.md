# 🧠 Autonomous Aerial Brains

> Embedded AI and Edge-Cognition Architectures designed to provide low-latency, fully autonomous vision, decision-making, and threat-reaction capabilities for unmanned aerial vehicles (UAVs) in EW-contested and GPS-denied environments.

---

### 📑 Technical Architecture & Execution Overview

| 📌 Section | 💡 Description & Technical Specifications |
| :--- | :--- |
| **System Philosophy** | EW-Resilient & Anti-Jamming Decentralized Edge Intelligence. Operates with complete RF-silence and zero telemetry dependency, rendering traditional EW jammers ineffective while navigating GPS-denied combat zones. |
| **System Architecture** | Lightweight neural networks optimized for embedded flight controllers and companion computers (e.g., NVIDIA Jetson / ARM Cortex), minimizing weight, power, and thermal footprint. |
| **Processing Performance** | **High-frequency sensor fusion & real-time path planning** running at high refresh rates to ensure split-second reaction times in contested airspace. |
| **Tech Stack & Environment** | C++, Python, ROS/ROS2 (Robot Operating System), OpenCV, TensorRT, Embedded Linux. |
| **Flight Dynamics & Control** | Autonomous waypoint navigation, optical flow obstacle avoidance, and dynamic target re-acquisition algorithms tailored for micro-UAV airframes. |
| **1. Repository Setup** | `git clone https://github.com/dyarewahab6-stack/Autonomous-Aerial-Brains.git` <br> `cd Autonomous-Aerial-Brains` |
| **2. Install Dependencies** | `pip install -r requirements.txt` <br> `# (Optional ROS workspace setup via catkin_make)` |
| **3. Run Autonomous Core**| `python main_brain.py --config configs/flight_profile_alpha.yaml --mode autonomous` |

---
