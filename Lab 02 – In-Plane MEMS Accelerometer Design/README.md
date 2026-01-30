# Lab 02 – In-Plane MEMS Accelerometer Design

**Course:** MEMS and Microsensors (Master, Polimi)  
**Date of work:** October 2025  
**Author:** Alberto Marrone

## 📌 Short Summary
-   **Design Specs:**
    -   Target Resonance Frequency: **4 kHz**.
    -   Process Thickness: **20 µm**.
    -   Mass side length: **400 µm**.
    -   Fold Length: **185 µm**.
-   **Structure:** Proof mass suspended by four folded springs (4-times folded) with nested holes for parallel plate readout.
-   **Simulations:**
    -   **Stationary:** Stiffness ($k$) evaluation under static load.
    -   **Eigenfrequency:** Modal analysis to match the 4 kHz target ($f_0$) and identify higher-order modes.
-   **Optimization:** Tuning of the fold width ($w_{fold}$) to achieve the target stiffness.

## 📂 Included Files
-   `CAD MEMS in-plane Accelerometer.mph` — COMSOL simulation file.
-   `Images/` — Mode shapes and displacement under 1g load.

### Visual Results
![Mode Shape](Images/Mode_Shape.png)
![Graph Description](Images/Mode_Shape.png)

## How to reproduce
1.  Open the `.mph` file in COMSOL Multiphysics.
2.  Run **Study 1 (Stationary)** to verify the displacement under static acceleration.
3.  Run **Study 2 (Eigenfrequency)** to visualize the first resonant mode.

## License
Simulation files: MIT License.
