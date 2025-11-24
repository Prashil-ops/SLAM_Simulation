# 🚀 SLAM Simulation: Laser-Based Obstacle Detection & Mapping

---

## 🎯 Project Overview

This project simulates a **2D laser sensor** that detects obstacles and generates a **point cloud map** in real time using **Python + Pygame**.

* 🔦 Laser-based obstacle sensing
* 👡 Mouse-controlled sensor position
* 🎟 Gaussian noise for realistic measurements
* 🗺 Dynamic point cloud mapping
* 📂 External map support

Perfect for **robotics enthusiasts** and **SLAM prototyping**.

---

## 🎜 Demo

### Animated GIF Preview

![Demo](https://raw.githubusercontent.com/prashil-ops/SLAM_Simulation/master/github_vdo.gif)



---

## 📂 Repository Structure

```
SLAM_Simulation/
│-- SLAM/
│    │-- github_video.gif
│    │-- github_video.mov
│    │-- env.py
│    │-- sensors.py
│    │-- map.png
│-- main.py
│-- README.md
```

---

## ▶️ How to Run

1. **Install dependencies**

```bash
pip install pygame numpy
```

2. **Run the simulation**

```bash
python main.py
```

3. **Move your mouse**
   The laser sensor follows your cursor and maps obstacles in real time.

---

## 🗑️ Key Features

* 360° laser scanning (60 rays per cycle)
* Distance + angle measurement with Gaussian uncertainty
* Point cloud storage and visualization on map
* Real-time interactive simulation

---

## 🌟 Future Improvements

* Full SLAM (EKF / ICP)
* Robot motion modeling
* Export point cloud (CSV/PCD)
* RRT path planning visualization
* Lidar-style circular animation

---

## ❤️ Credits

**Prashil Lamichhane 
Developed for learning and visualizing SLAM, robotics, and autonomous mapping.
