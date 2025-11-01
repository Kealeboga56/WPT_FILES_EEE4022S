
# Wireless Power Transfer for Microdrone Charging 🚁⚡

## Overview
This project focuses on the **design and simulation of a wireless power transfer (WPT) system** for the **M5Stamp Fly microdrone**, enabling **autonomous contactless charging** when the drone lands on a charging pad. The goal was to extend the drone’s operational time and reduce manual intervention during power replenishment.

The system was modeled and optimized using **ANSYS Electronics Desktop (Maxwell and HFSS)** along with **OptiSLang** to refine coil design parameters for improved coupling efficiency and power transfer performance.

---

## Project Objectives
- Develop a **transmitter (TX)** and **receiver (RX)** coil pair suitable for small-scale drone applications.  
- Optimize coil geometry to **maximize mutual inductance and efficiency**.  
- Simulate magnetic field distribution, coupling coefficient, and power transfer under different alignment conditions.  
- Validate design improvements through **parametric and sensitivity analyses**.  

---

## Simulation Files
The following files were used for electromagnetic and optimization simulations:

### 🌀 `Coil_Sensitivity_and_Optimization.opf`
- **Software:** OptiSLang  
- **Purpose:** Conducted sensitivity and optimization analysis on coil parameters (turns, spacing, diameter).  
- **Details:**  
  - Identified the most influential geometric parameters on coupling efficiency.  
  - Automated the optimization process to maximize power transfer.  

### 🧲 `Mini_Drone_Coils_2_OPTISLANG_FINAL.aedt`
- **Software:** ANSYS Electronics Desktop (HFSS/Maxwell)  
- **Purpose:** Main simulation file containing the 3D model of the transmitter and receiver coils.  
- **Details:**  
  - Includes material properties, boundary conditions, and excitation setup.  
  - Used to simulate magnetic field intensity, flux linkage, and coupling factor under various load and alignment conditions.  

---

## Key Results
- Achieved **efficient inductive coupling** suitable for low-power drone charging.  
- Demonstrated **robustness to minor misalignment**, enabling consistent charging performance.  
- Validated optimization results with significant improvements in mutual inductance and power transfer capability.  

---

## Tools & Technologies
- **ANSYS Electronics Desktop (HFSS / Maxwell)**  
- **OptiSLang**  
- **MATLAB** (for post-processing and data visualization)  

---

## Author
**Kealeboga Motlhankane**  
Electrical & Computer Engineering, University of Cape Town  
📧 kea.motlhankane@gmail.com 
📘 [GitHub Repository](https://github.com/Kealeboga56/WPT_FILES_EEE4022S.git)

---

## License
This project is for **academic and research purposes only**.  
Please credit the author when referencing or using the simulation setup.
