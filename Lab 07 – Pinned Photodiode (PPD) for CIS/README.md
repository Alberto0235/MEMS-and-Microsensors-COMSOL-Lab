# Lab 07 – Pinned Photodiode (PPD) for CIS

**Course:** MEMS and Microsensors (Master, Polimi)  
**Date of work:** December 2025  
**Author:** Alberto Marrone  
**Reference:** Course Instructor Design

## 📌 Short Summary
-   **Objective:** Simulation of a Pinned Photodiode (PPD) used in modern CMOS Image Sensors.
-   **Structure:** P++ pinned implant, N-type storage well, Transfer Gate (TG), and Floating Diffusion (FD).
-   **Physics Highlights:**
    -   **Potential Well:** Simulation of the "energy hole" where photogenerated electrons are collected, isolated from surface states (low dark current).
    -   **Charge Transfer:** Simulation of the Transfer Gate activation to move electrons from the PPD to the Floating Diffusion.
-   **Outcome:** Visualization of the complete charge transfer mechanism essential for Correlated Double Sampling (CDS).

## 📂 Included Files
-   `CAD Pinned photodiode.mph` — Reference simulation file.
-   `Images/` — Potential profile cuts showing the charge transfer barrier.

## How to reproduce
1.  Open `.mph` file in COMSOL Multiphysics (requires Semiconductor Module).
2.  Run the **Stationary Study** to simulate the device in the integration phase (TG low).
3.  Select the **1D Potential Plot** to verify the existence of the **Potential Well** (the "energy bucket") in the Pinned region.
4.  Change the global parameter `V_TG` (Transfer Gate Voltage) to High (e.g., 3.3V) and re-run to observe the barrier lowering and charge transfer to the Floating Diffusion.


## License
Educational Use.
