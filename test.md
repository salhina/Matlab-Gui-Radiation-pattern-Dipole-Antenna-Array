# MATLAB GUI: Radiation Pattern of Dipole Antennas & Antenna Arrays

## Project Overview
This project focuses on designing and visualizing the **radiation patterns** of standard **dipole antennas** with varying lengths using the **MATLAB GUI**. In the first part, we design and analyze **short**, **half-wave**, **full-wave**, and **variable-length dipoles**, extracting key characteristics like the **HPBW (Half Power Beamwidth)**. In the second part, we explore various **antenna array** configurations, with an emphasis on **phased antennas**. Parameters such as the number of elements, distances between elements, and phase gradient are varied to study their effect on the radiation pattern. Additionally, we cover special phase patterns like axial, radial, and oblique patterns for **ionospheric reflection**.

---

### **Project Demonstration**
✔️ **Dipoles**: Short, Half-wave, Full-wave, and Variable-length Dipoles (with HPBW calculation).  
✔️ **Antenna Array**: Phased antenna arrays with adjustable parameters such as the number of elements, distances, and phase gradient.

---

### Explainer Video

#### Project Overview and Demo
<p align="center">
<a href="https://www.youtube.com/watch?v=FCVu-16SsCk">
<img border="0" alt="Explainer Video" src="https://img.youtube.com/vi/FCVu-16SsCk/0.jpg">
</a>
</p>

Watch the explainer video to get an in-depth demonstration of the project's key features, including the radiation patterns of dipoles and antenna arrays. The video covers:
- Visualization of different dipole types (short, half-wave, full-wave, and variable-length)
- Interactive adjustments for phased antenna arrays
- Key metrics like **HPBW** and **phase patterns** for ionospheric reflection

**[Watch on YouTube](https://www.youtube.com/watch?v=FCVu-16SsCk)**

---

## Radiation Pattern of Dipole Antennas & Antenna Arrays

This MATLAB-based GUI project allows users to visualize and analyze radiation patterns of **dipole antennas** and **antenna arrays**. The software includes various features for comparing antenna types, adjusting parameters, and examining special cases, making it a valuable tool for **RF engineers** and **students** in **telecommunications**, **radar design**, and **satellite communication**.

#### Main Window of the MATLAB GUI
<p align="center"><img src="https://user-images.githubusercontent.com/52040368/169894000-4abe2abb-655f-4b38-b7e3-e65204731a7b.png"></p>
The main window of the GUI displays interactive elements for selecting dipole types and configuring antenna array parameters.

This project leverages MATLAB to explore the radiation patterns of dipole antennas and phased array antennas, providing valuable insights into antenna design and performance. It is designed for engineers and enthusiasts interested in antenna systems, phased arrays, and ionospheric reflection patterns.

### **Key Features**
- **Dipole Antenna Radiation Patterns**: Visualize radiation patterns for short, half-wave, full-wave, and variable-length dipoles. Compare different dipole types and analyze their behavior in various configurations.
- **HPBW Calculation**: Analyze and calculate the **Half Power Beamwidth (HPBW)** for various dipoles.
- **Special Phase Patterns**: Study **axial**, **radial**, and **oblique** phase patterns in the context of **ionospheric reflection**.
- **Antenna Array Design**: Design and simulate **phased array antennas** with adjustable parameters:
  - Number of elements
  - Distances between elements
  - Phase gradient
- **MATLAB GUI for Antenna Design**: Interactive tools for visualizing and analyzing radiation patterns, as well as adjusting antenna design parameters.

## Key Features

### 1. **Radiation Pattern of Dipole Antennas**
The main interface provides interactive features for visualizing the radiation patterns of different dipole antennas, including **short dipoles**, **half-wave dipoles**, **full-wave dipoles**, and **variable-length dipoles**. 

- **Polar Plot**: Displays the radiation patterns of various dipoles.
  - **Solid Black Line**: Represents the **short dipole**.
  - **Dashed Blue Line**: Another configuration of **short dipole**.
  - **Solid Blue Line**: Represents the **half-wave dipole** (λ/2).

#### Side Panel Features:
- **Basic Examples**:
  - **Directive Antenna with F(θ) = sinc(5θ)**
  - **Short Dipole (L << λ)**
  - **Half-Wave Dipole (L = λ/2)**
  - **Full-Wave Dipole (L = λ)**
- **Variable Linear Antenna**:
  - Specify the **L/λ** ratio, with a default value of **0.1**.
- **Comparison Between Base Antennas**:
  - Select checkboxes to compare different antenna types: **Short Dipole**, **Half-Wave Dipole**, **Full-Wave Dipole**.
  - Use the **DRAW** button to generate the comparison.
- **Additional Options**:
  - **Direction**: Choose between **Vertical** or **Horizontal** polarization.
  - **Radiation Type**: Select between **Field** or **Power** radiation.
  - **HPBW**: Displays the **Half Power Beamwidth (HPBW)**, with a default value of **90 degrees**.


#### Radiation Pattern of Dipole Antennas
<p align="center"><img src="https://user-images.githubusercontent.com/52040368/169894006-f591f7a2-0d97-4f64-953e-57500a607774.png"></p>
This image shows the radiation pattern visualization for different dipole antenna types, allowing for comparison between short, half-wave, full-wave, and variable-length dipoles.

### 2. **Radiation Pattern of Antenna Arrays**
This section allows for the analysis of **antenna arrays**. Users can adjust parameters such as the **number of elements**, **distance between elements**, and **phase gradient** to visualize how these affect the overall radiation pattern.

#### Main Interface:
- **Polar Plot**: Displays the radiation pattern of the antenna array for given input parameters.
- **Input Parameters**:
  - **Section 1: Network Function for 2 Antennas**: 
    - Distance (d/λ) set to **0.5**
    - Phase (φ) set to **0**
  - **Section 2: Network Function for n Antennas**:
    - Number of elements (n) set to **6**
    - Distance (d/λ) set to **0.4**
    - Phase (φ) set to **-144**
- **Plot Generation**: Press the **Tracer** button to generate the plot for the selected configuration.
- **Special Cases**: The software includes options to visualize **special cases** of antenna configurations.

#### Radiation Pattern of Array Antenna
<p align="center"><img src="https://user-images.githubusercontent.com/52040368/169894011-e6ed4132-50be-4fc9-8df9-3025de06ffd9.png"></p>
Here, the radiation pattern of a phased array antenna is displayed with adjustable parameters such as element count, distance between elements, and phase gradient.

### 3. **Special Case: 2 Dipoles Comparison**
This section lets users compare two dipole antennas under different configurations, adjusting both the **phase (φ)** and **distance (d/λ)** values. The following special cases are available:
- **φ = 0 and d = λ/2**
- **φ = 180 and d = λ/2**
- **φ = 90 and d = λ/4**

These configurations help optimize antenna performance for specific directional and radiation characteristics.

#### Special Case: 2 Dipoles Comparison
<p align="center"><img src="https://user-images.githubusercontent.com/52040368/169894016-81c0c984-77a7-438a-86e1-7d88451aee20.png"></p>
A comparison of radiation patterns for two dipole antennas placed at different orientations, illustrating the effect of alignment on the pattern.

### 4. **Special Case: Multiple Dipoles Comparison**
This section focuses on the analysis of **multiple dipole antennas** in different configurations. Users can compare the following special cases:
- **Alignment with Transverse Radiation** (φ = 0)
- **Positive Phase Gradient** (φ = 129)
- **Negative Phase Gradient** (φ = -129)
- **Alignment with Longitudinal Radiation**: (φ = -2πd/λ) where **d/λ = 0.4**.

Adjusting these parameters helps users understand how phase gradients and element spacing influence the array's radiation pattern.

#### Special Case: Multiple Dipoles Comparison
<p align="center"><img src="https://user-images.githubusercontent.com/52040368/169894018-e4c2b14e-0ae2-4413-bfab-30b2bc6fafc8.png"></p>
This image demonstrates the radiation pattern of a multi-element antenna array, showcasing the behavior of multiple dipoles in the array.

### 5. **About the Project**
- **Developer**: Nabil Salhi
- **Contact**: salhinabilpro@gmail.com
- **Created**: © 2013
- **Updated**: 2022
- 
<p align="center"><img src="https://user-images.githubusercontent.com/52040368/169894012-6a7b776e-e7ed-46af-b124-f7b128c26759.png"></p>


---

## **License**
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## **Acknowledgements**
- **MATLAB**: Used for antenna design and simulation.
- **Nabil Salhi**: Developer and maintainer of this project.

---

## 📎 *Resources & Links*
✔️ Access the project repository: [https://salhina.github.io/Matlab-Gui-Radiation-pattern-Dipole-Antenna-Array/](https://salhina.github.io/Matlab-Gui-Radiation-pattern-Dipole-Antenna-Array/)  
✔️ Learn more about *MATLAB antenna design*: [http://nabilsalhicv.me.ht/matlab-gui-designing-antennas/](http://nabilsalhicv.me.ht/matlab-gui-designing-antennas/)  
✔️ Reference page for this project: [https://sites.google.com/view/nabilsalhi/projects/project-2-matlab](https://sites.google.com/view/nabilsalhi/projects/project-2-matlab)  
✔️ Watch the explainer video on YouTube: [https://www.youtube.com/watch?v=FCVu-16SsCk](https://www.youtube.com/watch?v=FCVu-16SsCk)


---

## **Stay Connected**
- **Portfolio & Blog**: [Portfolio & Blog](https://salhina.github.io/)
- **LinkedIn Profile**: [LinkedIn](https://www.linkedin.com/in/salhi-nabil)

---

## **Stay Updated**
⭐ If you find this project helpful, consider starring the repository to show your support! Watch the repository for updates and improvements.

