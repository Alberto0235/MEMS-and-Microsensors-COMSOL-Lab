# Lab 05 – Pitch/Roll Gyroscope Design

**Course:** MEMS and Microsensors (Master, Polimi)  
**Date of work:** November 2025  
**Author:** Alberto Marrone  
**Reference:** Course Instructor Design

## 📌 Short Summary
-   **Objective:** Design of a gyroscope sensitive to in-plane angular rates (X or Y axis).
-   **Design Specs:**
    -   Target Drive Frequency: **22 kHz**.
    -   Mode Split: **1.1 kHz**.
    -   Process Thickness: **20 µm**.
-   **Structure:** Decoupled frame design.
    -   **Drive mode:** In-plane resonance of the outer frame (similar to the Yaw device).
    -   **Sense mode:** Torsional out-of-plane (tilting) motion of the inner masses, acting as torsional accelerometers for the Coriolis force.
-   **Analysis:** Optimization of the torsional springs to match the 22 kHz target while maintaining the correct mode order.

## 📂 Included Files
-   `CAD MEMS pitchroll Gyroscope.mph` — COMSOL simulation file.
-   `Images/` — Visualization of Drive (torsional) and Sense (piston) modes.

## How to reproduce
1.  Open `.mph` file in COMSOL Multiphysics.
2.  Run the **Eigenfrequency Study**.
3.  In the results list, identify the two critical modes:
    * **Drive Mode:** In-plane expansion/contraction of the outer frame (Target ≈ 22 kHz).
    * **Sense Mode:** Out-of-plane tiltingof the inner masses.
4.  Calculate the difference between these two frequencies to verify the **1.1 kHz mode split** specification.

## License
Simulation files: MIT License.
