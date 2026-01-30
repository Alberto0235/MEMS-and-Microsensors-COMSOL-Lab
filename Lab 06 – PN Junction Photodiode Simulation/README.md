# Lab 06 – PN Junction Photodiode Simulation

**Course:** MEMS and Microsensors (Master, Polimi)  
**Date of work:** November 2025  
**Author:** Alberto Marrone  
**Reference:** Course Instructor Design

## 📌 Short Summary
-   **Physics:** Semiconductor Module (2D).
-   **Structure:** N-type anodes on P-type epitaxial layer with P++ substrate.
-   **Simulations:**
    -   **Reverse Bias Analysis:** Stationary study of the diode under increasing reverse voltage.
    -   **Depletion Region:** Visualization of the expansion of the space charge region.
    -   **Electric Field:** Analysis of the peak field to prevent breakdown.
-   **Key Result:** Verification of the relationship between doping concentration and depletion width.

## 📂 Included Files
-   `CAD photodiode.mph` — Reference simulation file.
-   `Images/` — 2D plots of hole/electron concentration and electric potential.

## How to reproduce
1.  Open `.mph` file in COMSOL Multiphysics (requires Semiconductor Module).
2.  Run the **Stationary Study**. The solver will sweep the reverse bias voltage (e.g., from 0V to 5V).
3.  Go to **Results > 2D Plot Group**:
    * Visualize **Electric Potential** to see the voltage drop across the junction.
    * Visualize **Log(Carrier Concentration)** to observe the depletion region boundaries.
4.  (Optional) Use a **1D Cut Line** to plot the electric field peak at the junction interface.

## License
Educational Use.
