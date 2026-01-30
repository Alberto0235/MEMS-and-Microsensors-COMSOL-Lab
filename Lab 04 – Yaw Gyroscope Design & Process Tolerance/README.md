# Lab 04 – Yaw Gyroscope Design & Process Tolerance

**Course:** MEMS and Microsensors (Master, Polimi)  
**Date of work:** October 2025  
**Author:** Alberto Marrone

## 📌 Short Summary
-   **Design Specs:**
    -   Drive Mode Frequency: **20 kHz**.
    -   Drive-Sense Mismatch ($\Delta f$): **1.1 kHz**.
    -   Max Area: **400 x 800 µm²**.
-   **Simulations:**
    -   **Mode Matching:** Tuning of suspension springs to set the separation between the in-phase drive mode and the sense mode.
    -   **Parametric Sweep:** Analysis of **Over-etching / Under-etching** effects ($\pm 0.1 \mu m$ to $\pm 1 \mu m$) on the frequency split.
-   **Outcome:** Redesign of spring widths ($w_f, w_d$) to ensure robustness against process variations.

## 📂 Included Files
-   `Yaw_Gyroscope.mph` — COMSOL simulation file.
-   `Images/` — Frequency sweep plots and mode shapes.

## How to reproduce
1.  Run the **Parametric Sweep** study.
2.  Check the 1D Plot Group to see how $f_{drive}$ and $f_{sense}$ cross or diverge with etching tolerances.

## License
Simulation files: MIT License.
