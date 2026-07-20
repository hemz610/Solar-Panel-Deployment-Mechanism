# Solar Panel Deployment Mechanism

![GitHub](https://img.shields.io/badge/CAD-NX%202412-blue)
![Simulation](https://img.shields.io/badge/Simulation-Simcenter%203D%20Motion%202506-green)
![Status](https://img.shields.io/badge/Status-Work%20In%20Progress-orange)

## Overview

This project presents the design and simulation of a **single-axis spacecraft solar panel deployment mechanism** developed using **Siemens NX 2412** and **Simcenter 3D Motion 2506**.

The objective is to model a realistic deployment sequence where the solar panel rotates smoothly from its stowed configuration to its deployed position through a revolute hinge driven by a stepper motor.

This repository will continue to grow with:

- Motion Simulation
- Structural Analysis (FEA)
- Thermal Analysis
- Design Optimization

---

## Project Objectives

- Design a compact deployable solar panel mechanism
- Simulate panel deployment using multibody dynamics
- Perform structural analysis under deployment loads
- Evaluate thermal behaviour under space environment conditions
- Document the complete engineering workflow

---

# Software Used

| Software | Purpose |
|-----------|---------|
| Siemens NX 2412 | CAD Modeling |
| Simcenter 3D Motion 2506 | Multibody Dynamics |
| Simcenter 3D Structures *(Upcoming)* | Structural Analysis |
| Simcenter 3D Thermal *(Upcoming)* | Thermal Analysis |

---

# CAD Assembly

The mechanism consists of:

- Base Plate
- Motor Mount
- Stepper Motor
- Motor Shaft
- Bearing Housings
- Ball Bearings
- Revolute Hinge
- Solar Panel
- Standard Fasteners

---

# Motion Simulation

The deployment mechanism was modeled in Simcenter 3D Motion using:

- Motion Bodies
- Revolute Joint
- Joint Driver
- Time-based Motion Function

Deployment Sequence

```
Stowed Position (0°)
        │
        ▼
Controlled Rotation
        │
        ▼
Fully Deployed Position (90°)
```

---

# Repository Structure

```
Solar-Panel-Deployment-Mechanism/
│
├── CAD/
│   ├── Hardware Library/
│   ├── *.prt
│
├── Motion/
│   ├── *.sim
│   ├── Results/
│
├── Structural/          (Coming Soon)
│
├── Thermal/             (Coming Soon)
│
├── Images/
│
├── Videos/
│
├── README.md
│
└── LICENSE
```

---

# Current Progress

- [x] CAD Design
- [x] Motion Assembly
- [x] Revolute Joint
- [x] Motion Driver
- [x] Deployment Simulation
- [ ] Structural Analysis
- [ ] Thermal Analysis
- [ ] Design Optimization
- [ ] Final Report

---

# Upcoming Work

## Structural Analysis

Future work will include:

- Static Structural Analysis
- Modal Analysis
- Stress Distribution
- Factor of Safety Evaluation

---

## Thermal Analysis

Future work will include:

- Solar Radiation
- Temperature Distribution
- Thermal Expansion
- Orbital Thermal Cycling

---

# Results

## Motion Simulation

---

## Structural Analysis

Coming Soon

---

## Thermal Analysis

Coming Soon

---

# Future Improvements

- Motor torque optimization
- Deployment locking mechanism
- Flexible solar panel modelling
- Space environment loading
- Lightweight topology optimization

---

# Author

**Hemanth**

Astronautical Engineering

University of Leicester

GitHub: https://github.com/hemz610

---

# License

This project is released under the MIT License.
