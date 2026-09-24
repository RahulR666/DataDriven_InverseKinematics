# Data-Driven Inverse Kinematics in 2D and 3D

A robotics project exploring a data-driven approach to inverse kinematics for multi-link manipulators in 2D and 3D.

The project generates manipulator configurations, builds datasets relating end-effector positions to joint configurations, and uses the resulting data to study inverse-kinematics prediction.

---

## Overview

Inverse kinematics determines the joint configuration required for a robotic manipulator to reach a desired end-effector position.

For high-dimensional manipulators, analytical solutions can become difficult to derive or may have multiple valid solutions.

This project explores a data-driven alternative by generating forward-kinematics samples and learning the relationship between end-effector coordinates and joint configurations.

The implementation includes both:

- 2D manipulator configurations
- 3D manipulator configurations

---

## Project Structure

```text
data-driven-inverse-kinematics/
├── src/
│   ├── generate_dataset_2d.py
│   ├── generate_dataset_3d.py
│   ├── inverse_kinematics_2d.py
│   └── inverse_kinematics_3d.py
│
├── data/
│   ├── seven_link_dataset_2d.csv
│   └── seven_link_dataset_3d.csv
│
├── results/
├── requirements.txt
└── README.md
