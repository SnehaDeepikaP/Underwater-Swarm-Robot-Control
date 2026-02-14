# Underwater-Swarm-Robot-Control

An AI-driven swarm control framework for coordinating multiple Autonomous Underwater Vehicles (AUVs) in dynamic underwater environments.
Paper Title: Artificial Intelligence Algorithms for Swarm-Based AUV Control
---

## 📌 Abstract

This project presents a robust artificial intelligence framework for controlling a swarm of Autonomous Underwater Vehicles (AUVs). The system integrates multiple AI-based algorithms to enable real-time formation control, adaptive path planning, and collision avoidance in unpredictable marine environments.

Unlike traditional centralized control systems, this framework emphasizes decentralized decision-making, robustness to environmental disturbances (such as water currents), and scalability to larger swarms.

---

## 🎯 Motivation

Autonomous Underwater Vehicles (AUVs) are widely used for:

- Marine exploration  
- Hydrographic surveys  
- Environmental monitoring  
- Defense and surveillance missions  

However, operating multiple AUVs as a swarm introduces significant challenges:

- 🌊 Unpredictable water currents  
- 📡 Limited underwater communication  
- 🐟 Dynamic moving obstacles  
- ⚙️ Real-time coordination complexity  

Traditional control methods lack adaptability and robustness under these conditions.  
This project aims to address these challenges using AI-based swarm intelligence techniques.

---

## 🎯 Objective

The primary objectives of this project are:

1. **Formation Control** – Maintain stable swarm formations  
2. **Task Allocation** – Efficient distribution of mission roles  
3. **Dynamic Path Planning** – Real-time route adjustment  
4. **Collision Avoidance** – Avoid static and moving obstacles  

---
<!--
## 🧠 Algorithms Integrated

This framework integrates three complementary algorithms:

### 1️⃣ Boids Algorithm (Local Swarm Intelligence)

- Alignment  
- Cohesion  
- Separation  

✔ Modified to compensate for underwater currents  
✔ Prevents swarm dispersion  

---

### 2️⃣ Probabilistic Roadmap (PRM)

- Global path planning  
- Obstacle avoidance  

✔ Enhanced for real-time recalculation  
✔ Handles dynamic obstacles  

---

### 3️⃣ Leader-Follower Strategy

- Structured swarm coordination  
- Velocity synchronization  

✔ Improved with water-current compensation  
✔ Followers dynamically adjust relative to leader  

---
-->
## 🏗️ System Framework

The integrated AI framework works as follows:

- **PRM** provides global path planning.
- **Boids** ensures local coordination and collision avoidance.
- **Leader-Follower** maintains structured formation.

Each AUV makes decentralized decisions based on:

- Local sensing
- Neighbor states
- Environmental conditions

This ensures scalability and robustness.

---

## 🛠️ Technologies Used

- Python  
- VPython (3D real-time visualization)  
- NumPy (numerical computations)  
- Matplotlib (performance analysis & plotting)  

---

## 🌊 Simulation Environment

The simulation includes:

- Multiple AUV agents
- Static obstacles (rocks, coral structures)
- Moving obstacles (marine life simulation)
- Environmental water currents

---

## 📊 Results & Performance Metrics

The system was evaluated using:

### 🔹 Depth vs Time
- Stable descent patterns
- Energy-efficient motion observed in specific robots

### 🔹 Distance vs Time
- Effective displacement toward mission targets
- Oscillations indicate adaptive obstacle avoidance

### 🔹 Velocity vs Time
- Stabilized speeds (~0.5–0.6 m/s)
- Temporary fluctuations reflect real-time adjustments

### 🔹 Distance to Target
- All AUVs reduced initial distance (~25m) to <5m
- Successful coordinated convergence

---

## 🔬 Key Observations

- Swarm maintained stable formation despite environmental disturbances.
- Real-time PRM recalculations prevented collisions.
- Boids ensured cohesion under current influence.
- Leader-follower mechanism enabled structured movement.


