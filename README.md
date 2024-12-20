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
- `Manual_Calculations`: Includes detailed step-by-step calculations for designing the antenna.  
- `Simulation_Results`: Contains radiation pattern, gain, VSWR, and S11 parameters.  
- `3D_Models`: Optional 3D models for visualization.  

---

## Design Calculations  
The design of the microstrip antenna is based on the following specifications and equations:  

1. **Target Frequency**: 2.4 GHz  
2. **Dielectric Constant**: εr = 4.3  
3. **Substrate Thickness**: h = 1.6 mm  
4. **Conductor Thickness**: t = 0.035 mm  

<img src="Micostrip Image/Parameters.jpg" width="500"/>

---

## Simulation Results  
Simulated parameters include:  
- **Radiation Pattern**: Omni-directional in the H-plane.  
- **Gain**: Achieved gain is approximately 5 dBi.  
- **VSWR**: ≤ 1.5 at the target frequency.  
- **S11 Parameter**: Below -10 dB at 2.4 GHz.
- 
<img src="Micostrip Image/Top Layer.jpg" width="500"/>
<img src="Micostrip Image/Bottom Layer.jpg" width="500"/>
<img src="Micostrip Image/L=29_422.jpg" width="500"/>
<img src="Micostrip Image/Pre-specive.jpg" width="500"/>
---

## Contributions  
Contributions are welcome! Feel free to submit a pull request or raise an issue for any improvements or suggestions.
