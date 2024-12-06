# 2.4 GHz Microstrip Antenna Design for ISM Band

## Overview  
This project demonstrates the design and implementation of a **microstrip antenna** for the **2.4 GHz ISM band**. The design includes all necessary manual calculations, layout files, and simulation results, providing a comprehensive guide for creating a functional antenna for wireless applications such as Wi-Fi, Bluetooth, and IoT devices.

The goal of this project is to offer a detailed and practical example of microstrip antenna design, focusing on performance optimization for the 2.4 GHz frequency.

---

## Features  
- **Frequency**: Designed for 2.4 GHz (ISM band).  
- **Substrate Material**: FR4 with a relative permittivity (εr) of 4.3.  
- **Substrate Thickness (h)**: 1.6 mm.  
- **Conductive Material**: Copper with a thickness of 0.035 mm.  
- **Design Methodology**: Manual calculations for all critical parameters (length, width, feed, etc.).  
- **Simulation**: Results verified using software tools like CST, HFSS, or similar.  
- **Applications**: Wi-Fi, Bluetooth, IoT devices, and other wireless communication systems.

---

## Project Structure  
This repository contains the following key files and directories:  
- `Manual_Calculations/`: Includes detailed step-by-step calculations for designing the antenna.  
- `Schematic_Layout/`: Gerber and PCB design files for fabricating the antenna.  
- `Simulation_Results/`: Contains radiation pattern, gain, VSWR, and S11 parameters.  
- `3D_Models/`: Optional 3D models for visualization.  

---

## Design Calculations  
The design of the microstrip antenna is based on the following specifications and equations:  

1. **Target Frequency**: 2.4 GHz  
2. **Dielectric Constant**: εr = 4.3  
3. **Substrate Thickness**: h = 1.6 mm  
4. **Conductor Thickness**: t = 0.035 mm  

Key equations used for the design:  

- **Width of the Patch (W)**:  
  \[
  W = \frac{c}{2f_r \sqrt{\frac{\epsilon_r + 1}{2}}}
  \]  

- **Effective Dielectric Constant (ε_eff)**:  
  \[
  \epsilon_{\text{eff}} = \frac{\epsilon_r + 1}{2} + \frac{\epsilon_r - 1}{2}\left(1 + 12\frac{h}{W}\right)^{-\frac{1}{2}}
  \]  

- **Length of the Patch (L)**:  
  \[
  L = \frac{c}{2f_r \sqrt{\epsilon_{\text{eff}}}} - 2\Delta L
  \]  

- **Length Extension (ΔL)**:  
  \[
  \Delta L = 0.412h \frac{(\epsilon_{\text{eff}} + 0.3)(\frac{W}{h} + 0.264)}{(\epsilon_{\text{eff}} - 0.258)(\frac{W}{h} + 0.8)}
  \]  

---

## Simulation Results  
Simulated parameters include:  
- **Radiation Pattern**: Omni-directional in the H-plane.  
- **Gain**: Achieved gain is approximately 5 dBi.  
- **VSWR**: ≤ 1.5 at the target frequency.  
- **S11 Parameter**: Below -10 dB at 2.4 GHz.  

---

## How to Use  
1. **Download the repository**: Clone or download the files to access schematics, layouts, and simulation data.  
2. **Fabricate the PCB**: Use the provided Gerber files to manufacture the antenna.  
3. **Simulate**: Verify and optimize using software tools like CST or HFSS.  
4. **Test**: Integrate with a matching network to achieve a 50 Ω impedance and test in the desired application.  

---

## Contributions  
Contributions are welcome! Feel free to submit a pull request or raise an issue for any improvements or suggestions.
