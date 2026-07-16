
# Terrain-Adaptive Fuzzy Braking System for Cars

## Overview

The **Terrain-Adaptive Fuzzy Braking System** is an intelligent automotive safety system designed to provide adaptive braking based on real-time driving conditions. The system determines the appropriate braking intensity by considering three key parameters: **vehicle speed**, **distance to an obstacle**, and **road surface friction**. It combines **Mamdani Type-1 Fuzzy Logic** with the **Adaptive Neuro-Fuzzy Inference System (ANFIS)** to achieve smooth, human-like braking while improving adaptability and accuracy through machine learning. 

---

## Features

* Intelligent terrain-adaptive braking
* Mamdani Type-1 Fuzzy Logic Controller
* Adaptive Neuro-Fuzzy Inference System (ANFIS)
* Real-time brake force estimation
* Simulation using MATLAB/Simulink
* Arduino-based sensor simulation using Wokwi
* Rule-based and data-driven braking comparison
* Smooth and adaptive braking decisions
* Improved vehicle safety and stability

---

## Project Objectives

* Design an intelligent braking controller using fuzzy logic.
* Adapt braking force based on vehicle speed, obstacle distance, and terrain conditions.
* Compare the performance of Mamdani Fuzzy Logic and ANFIS.
* Improve braking smoothness, stability, and responsiveness under varying driving conditions.

---

## System Architecture

```text
Vehicle Speed
        │
Obstacle Distance
        │
Terrain Friction
        │
        ▼
Data Acquisition
        │
        ▼
Mamdani Fuzzy Logic Controller
        │
        ├──────────────► Brake Force (%)
        │
        ▼
ANFIS Model
        │
        ▼
Performance Comparison
```

---

## Hardware & Software

### Hardware

* Arduino (Wokwi Simulation)
* Ultrasonic Sensor (Obstacle Distance)
* Potentiometer (Vehicle Speed)
* Potentiometer (Terrain Friction Simulation)

### Software

* MATLAB
* Simulink
* Fuzzy Logic Toolbox
* ANFIS Toolbox
* Wokwi Simulator

---

## Methodology

The system uses three input variables:

* Vehicle Speed
* Distance to Obstacle
* Terrain Friction

These inputs are processed by a **Mamdani Type-1 Fuzzy Inference System**, where fuzzy membership functions and expert-defined rules determine the braking intensity. The same dataset is then used to train an **ANFIS model**, which automatically optimizes the membership functions using a hybrid learning algorithm. The performance of both approaches is compared through simulation under different driving scenarios. 

---

## Fuzzy Logic Controller

### Inputs

* Vehicle Speed
* Obstacle Distance
* Terrain Friction

### Output

* Brake Force (%)

### Membership Functions

**Speed**

* Low
* Medium
* High

**Distance**

* Near
* Medium
* Far

**Terrain**

* Slippery
* Normal
* Rough

**Brake Force**

* Light
* Moderate
* Hard

---

## ANFIS Model

The ANFIS controller combines fuzzy inference with neural network learning to improve braking performance. It automatically adjusts membership functions and fuzzy rules using training data, enabling more accurate and adaptive brake force prediction under dynamic driving conditions. 

---

## Simulation Results

The project demonstrates that:

* Mamdani Fuzzy Logic provides smooth and interpretable braking decisions.
* ANFIS improves prediction accuracy through learning.
* Brake intensity adapts according to speed, obstacle distance, and terrain conditions.
* The system maintains stability across different driving scenarios. 

---

## Technologies Used

* MATLAB
* Simulink
* Fuzzy Logic Toolbox
* ANFIS
* Arduino
* Wokwi
* Fuzzy Logic
* Soft Computing
* Intelligent Control Systems

---

## Future Scope

* Integration with real vehicle braking systems
* Real-time implementation using embedded hardware
* Sensor fusion using LiDAR and cameras
* Integration with Advanced Driver Assistance Systems (ADAS)
* Autonomous emergency braking
* Edge AI implementation for faster decision-making

---

## Team Members

* Sanjana Mudhale G
* Aparajitha Selvamani

**Project Guide**

* Dr. Vijayachandrakala K. R. M.

---

## References

* Zadeh, L. A. – Fuzzy Logic Systems
* Jang, J. S. R. – Adaptive Neuro-Fuzzy Inference System (ANFIS)
* MATLAB Fuzzy Logic Toolbox Documentation
* MATLAB ANFIS Documentation 

---

## License

This project was developed for academic purposes as part of the B.Tech curriculum in Electrical and Electronics Engineering at **Amrita Vishwa Vidyapeetham**.
