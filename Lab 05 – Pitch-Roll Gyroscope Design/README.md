# Lab 05 – Pitch/Roll Gyroscope Design

**Course:** MEMS and Microsensors (Master, Polimi)  
**Date of work:** November 2025  
**Author:** Alberto Marrone

## 📌 Short Summary
-   **Objective:** Design of a gyroscope sensitive to in-plane angular rates (X or Y axis).
-   **Design Specs:**
    -   Target Drive Frequency: **22 kHz**.
    -   Mode Split: **1.1 kHz**.
-   **Structure:** Decoupled frame design.
    -   **Drive:** Torsional outer frame.
    -   **Sense:** Inner masses moving out-of-plane (Coriolis acceleration).
-   **Analysis:** Optimization of the torsional springs ($k = 2G w^3 h / 3l$) to hit the 22 kHz target while maintaining the correct mode order.

## 📂 Included Files
-   `PitchRoll_Gyro.mph` — COMSOL simulation file.
-   `Images/` — Visualization of Drive (torsional) and Sense (piston) modes.

## License
Simulation files: MIT License.
