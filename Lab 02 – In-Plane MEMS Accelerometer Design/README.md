# Lab 02 – In-Plane MEMS Accelerometer Design

**Course:** MEMS and Microsensors (Master, Polimi)  
**Date of work:** October 2025  
**Author:** Alberto Marrone

## 📌 Short Summary
-   **Design Specs:** -   Target Resonance Frequency: **4 kHz**.
    -   Process Thickness: **20 µm**.
    -   Mass side length: **400 µm**.
-   **Structure:** Proof mass suspended by four folded springs (4-times folded) with nested holes for parallel plate readout.
-   **Simulations:**
    -   **Stationary:** Stiffness ($k$) evaluation under static load.
    -   **Eigenfrequency:** Modal analysis to match the 4 kHz target ($f_0$) and identify higher-order modes.
-   **Optimization:** Tuning of the fold width ($w_{fold}$) to achieve the target stiffness.

## 📂 Included Files
-   `InPlane_Accel.mph` — COMSOL simulation file.
-   `Images/` — Mode shapes and displacement under 1g load.

## How to reproduce
1.  Open the file and run **Study 1 (Stationary)** for stiffness verification.
2.  Run **Study 2 (Eigenfrequency)** to visualize the first resonant mode.

## License
Simulation files: MIT License.
