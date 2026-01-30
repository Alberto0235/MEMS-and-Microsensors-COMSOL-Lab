# Lab 01 – Introduction to Electrostatic Actuation

**Course:** MEMS and Microsensors (Master, Polimi)  
**Date of work:** October 2024  
**Author:** Alberto Marrone

## 📌 Short Summary
-   **Objective:** Introduction to multiphysics simulation (Electrostatics) and evaluation of fringing field effects.
-   **Simulation:** Analysis of an in-plane comb-finger capacitor vs. parallel plate approximation.
-   **Key Findings:** The simulation quantified the parasitic capacitance contribution from fringing fields ($C_{fringing}$) and the effect of the trench depth on the electric field distribution ($E_x, E_y$).
-   **Method:** Stationary analysis comparing theoretical capacitance $C = \epsilon A / d$ against FEM derived values.

## 📂 Included Files
-   `Capacitance_Model.mph` — COMSOL simulation file.
-   `Images/` — Plots of electric field streamlines and potential distribution.

## How to reproduce
1.  Open `.mph` file in COMSOL Multiphysics.
2.  Run the **Stationary Study**.
3.  Navigate to "Derived Values" to view the computed global capacitance.

## License
Simulation files: MIT License.
