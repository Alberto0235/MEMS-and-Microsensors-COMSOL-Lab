# 🔬 MEMS and Microsensors Laboratory – COMSOL Simulations

**Course:** MEMS and Microsensors (Master's Degree in Electronic Engineering)  
**University:** Politecnico di Milano  
**Academic Year:** 2025-2026  
**Scope:** Master's degree course in Electronics Engineering  

---

## 📌 Overview

This repository collects all the laboratory works carried out during the **MEMS and Microsensors course**, providing a complete record of the Finite Element Analysis (FEA) simulations performed. Each lab includes the design, physics setup, and simulation of various micro-electromechanical and optical sensors using **COMSOL Multiphysics**.

The laboratories included are:

1.  **Lab 01 – Electrostatic Capacitance Simulation** Investigation of electrostatic physics in micro-domains. Comparison between analytical parallel-plate approximations and FEM simulations to quantify fringing field effects in comb-drive structures.

2.  **Lab 02 – In-Plane Accelerometer Design** Design of a MEMS accelerometer for X/Y-axis sensing. The study involves stationary analysis for stiffness calculation ($k$) and eigenfrequency analysis to determine the fundamental resonant mode ($f_0$).

3.  **Lab 03 – Torsional Accelerometer Design** Design of an out-of-plane (Z-axis) accelerometer based on a torsional mass. The goal was to match the sensitivity and bandwidth of the in-plane device to complete a 3-axis IMU module.

4.  **Lab 04 – Yaw Gyroscope Design** Analysis of a frame-based gyroscope for Z-axis rotation sensing. The lab focuses on tuning the Drive and Sense modes, analyzing the Coriolis effect, and managing process imperfections (over/under-etching).

5.  **Lab 05 – Pitch/Roll Gyroscope Design** Design of a torsional gyroscope for detecting in-plane angular rates (Pitch/Roll). The project involves optimizing the suspension system to decouple drive and sense motions.

6.  **Lab 06 – PN Junction Photodiode** Simulation of a standard reverse-biased PN photodiode. Analysis of the depletion region width, electric field distribution, and photocurrent generation mechanisms using the Semiconductor Module.

7.  **Lab 07 – Pinned Photodiode (PPD)** Advanced simulation of a Pinned Photodiode for CMOS Image Sensors (CIS). The study demonstrates the creation of potential wells for charge collection and the complete charge transfer mechanism to the Floating Diffusion.

---

## 🛠️ Tools and Software Used

-   **COMSOL Multiphysics** – Primary FEA tool (Modules: *MEMS, Structural Mechanics, Electrostatics, Semiconductor*).
-   **Solid Mechanics Module** – For eigenfrequency and stationary displacement analysis.
-   **Electrostatics Module** – For capacitance matrices and voltage actuation.
-   **Semiconductor Module** – For charge transport and potential barrier simulations.

---

## 📂 Repository Structure

Each lab folder contains the **simulation files (.mph)** and representative images of the results.

*Note: The PDF reports/instructions are not included, but a summary of the work is provided in each folder.*

---

## ✅ Learning Outcomes

-   Proficiency in **multiphysics FEA simulation** (Mechanical, Electrostatic, Optical).
-   Understanding of **MEMS design constraints** (process thickness, minimum feature size).
-   Analysis of **modal behavior** and frequency matching in inertial sensors.
-   Insight into **semiconductor device physics** (depletion regions, potential wells).
-   Evaluation of **process variations** (etching tolerances) on sensor performance.

---

## 📜 License

-   Original Designs/Simulations: **MIT License**
-   Course Reference Designs: **Educational Use / Reference**

---

## Notes

This repository documents the work performed during the **MEMS and Microsensors** course at Politecnico di Milano.
* **Labs 01-05:** Developed individually as part of the coursework.
* **Labs 06-07:** Based on reference designs provided by the course instructors to illustrate semiconductor physics concepts.
