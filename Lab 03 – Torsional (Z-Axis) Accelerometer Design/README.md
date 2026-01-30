# Lab 03 – Torsional (Z-Axis) Accelerometer Design

**Course:** MEMS and Microsensors (Master, Polimi)  
**Date of work:** October 2025  
**Author:** Alberto Marrone  
**Reference:** Course Instructor Design

## 📌 Short Summary
-   **Objective:** Completing a 3-axis IMU module by designing a Z-axis sensor matching the in-plane performance.
-   **Design Specs:**
    -   Target Sensitivity: **5 fF/g**.
    -   Resonance Frequency: **3-5 kHz**.
    -   Vertical Gap: **1.4 µm**.
    -   Process Thickness: **30 µm**.
-   **Structure:** Asymmetric torsional mass with parallel plate electrodes.
-   **Analysis:** Calculation of rotational stiffness ($k_{\theta}$) and moment of inertia ($I$) to tune the frequency $\omega_0 = \sqrt{k/I}$.

## 📂 Included Files
-   `CAD MEMS torsional Accelerometer.mph` — COMSOL simulation file.
-   `Images/` — Torsional mode visualization (tilting motion).

## How to reproduce
1.  Open `.mph` file in COMSOL Multiphysics.
2.  Run **Study 1 (Eigenfrequency)** to compute the vibration modes.
3.  Check the resulting frequencies in the **Eigenvalues** table: verify that the fundamental torsional mode falls within the **3-5 kHz** target range.
4.  View the **3D Plot Group** to confirm the mode shape corresponds to a tilting motion around the central axis.

## License
Simulation files: MIT License.
