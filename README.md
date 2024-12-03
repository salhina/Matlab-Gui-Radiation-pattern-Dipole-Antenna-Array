# MATLAB GUI: Radiation Pattern of Dipole Antennas & Antenna Arrays

## Project Overview

This project focuses on designing and visualising the **radiation patterns** of standard **dipole antennas** with varying lengths using the **MATLAB GUI**. The GUI allows for the analysis of both individual dipole antennas and **phased antenna arrays**.

The project is divided into two main parts:

1. **Dipole Antenna Analysis:** This section allows users to design and analyse **short**, **half-wave**, **full-wave**, and **variable-length dipoles**. Key characteristics such as the **HPBW (Half Power Beamwidth)** can be extracted and visualised.
2. **Antenna Array Analysis:** This section allows users to explore various **antenna array** configurations, with an emphasis on **phased antennas**. Parameters such as the number of elements, distances between elements, and phase gradient can be adjusted to study their effect on the radiation pattern. Additionally, special phase patterns like axial, radial, and oblique patterns for **ionospheric reflection** are covered.

## Key Features

* **Dipole Antenna Radiation Patterns:** Visualise radiation patterns for short, half-wave, full-wave, and variable-length dipoles. Compare different dipole types and analyse their behaviour in various configurations.
* **HPBW Calculation:** Analyse and calculate the **Half Power Beamwidth (HPBW)** for various dipoles.
* **Special Phase Patterns:** Study **axial**, **radial**, and **oblique** phase patterns in the context of **ionospheric reflection**.
* **Antenna Array Design:** Design and simulate **phased array antennas** with adjustable parameters:
    * Number of elements
    * Distances between elements
    * Phase gradient
* **MATLAB GUI for Antenna Design:** Interactive tools for visualising and analysing radiation patterns, as well as adjusting antenna design parameters.

## Explainer Video

### Project Overview and Demo
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

## GUI Overview


Main Window of the MATLAB GUI
<p align="center"><img src="https://user-images.githubusercontent.com/52040368/169894000-4abe2abb-655f-4b38-b7e3-e65204731a7b.png"></p>
The GUI is divided into two main sections:

### 1. Radiation Pattern of Dipole Antennas

This section allows for the analysis of individual dipole antennas. The interface includes:
<p align="center"><img src="https://user-images.githubusercontent.com/52040368/169894006-f591f7a2-0d97-4f64-953e-57500a607774.png"></p>

* **Polar Plot:** Displays the radiation pattern of the selected dipole antenna.
* **Antenna Type Selection:** Allows users to select from short, half-wave, full-wave, and variable-length dipoles.
* **Parameter Input:** Allows users to input the desired length of the dipole antenna. For variable-length dipoles, the length is specified as a ratio to the wavelength (L/λ).
* **Additional Options:** May include options such as:
    * **Direction:** Choose between **Vertical** or **Horizontal** polarisation.
    * **Radiation Type:** Select between **Field** or **Power** radiation.
    * **HPBW Display:** Displays the calculated HPBW of the antenna.

### 2. Radiation Pattern of Antenna Arrays

This section allows for the analysis of antenna arrays. Users can adjust parameters such as the number of elements, distance between elements, and phase gradient to study their effect on the radiation pattern. The section also includes functionalities to visualise special cases of two and multiple dipole configurations.

**Main Interface:**
<p align="center"><img src="https://user-images.githubusercontent.com/52040368/169894011-e6ed4132-50be-4fc9-8df9-3025de06ffd9.png"></p>

* **Polar Plot:** Displays the radiation pattern of the antenna array for given input parameters.
* **Input Parameters:** Allows users to input parameters such as:
    * Number of elements
    * Distance between elements (specified as a ratio to the wavelength, d/λ)
    * Phase difference between elements (φ)
* **Plot Generation:** A button to trigger the simulation and generate the radiation pattern.
* **Special Cases:** Options to visualise pre-defined special cases of antenna array configurations. These are categorised by the number of dipoles in the array.

**Special Cases:**

* **Two-Dipole Cases:** Allows users to compare the radiation patterns of two dipoles under specific configurations. The configurations may include variations in the phase difference (φ) and distance between the dipoles (d/λ).
* **Multiple-Dipole Cases:** Allows users to analyse the radiation patterns of arrays with multiple dipoles. The configurations may include different phase gradients and element spacings, showcasing how these factors influence the overall radiation pattern.






#### Two-Dipole Cases: Association de Plusieurs Antennes Collinaires (Association of Two Collinear Antennas)

This section allows users to compare the radiation patterns of two dipoles under specific configurations. The configurations can vary based on:


- **Phase Difference (φ):** The phase shift between the two antennas, which can significantly influence the directionality and shape of the radiation pattern.
- **Distance between Dipoles (d/λ):** The distance between the two dipoles, expressed as a ratio to the wavelength (λ). Adjusting this distance can affect the coupling between antennas and the resulting interference pattern.

##### Input Parameters:
- **Number of Antennas (n):** Set to **2** (for two dipoles).
- **Distance between Dipoles (d/λ):** Set to **0.4** (a typical value for demonstrating collinear antenna patterns).
- **Phase Difference (φ):** Set to **-144** degrees (this can be adjusted to study different radiation patterns and interference effects).

##### Buttons:
- **Tracer (Plot):** Generate the radiation pattern based on the input parameters (phase difference and distance).
- **Cas Spéciaux (Special Cases):** Open a menu with predefined special cases for comparing two dipoles.

##### Special Cases Menu (for Two Antennas):
<p align="center"><img src="https://user-images.githubusercontent.com/52040368/169894016-81c0c984-77a7-438a-86e1-7d88451aee20.png"></p>

- **φ = 0 and d = λ/2:** This configuration places the two antennas in-phase (φ = 0) with a half-wavelength distance between them (d = λ/2), creating constructive interference and a directional radiation pattern.
- **φ = 180 and d = λ/2:** With a phase difference of 180 degrees (out of phase) and a half-wavelength separation, this configuration creates destructive interference, producing a radiation pattern with a null at certain angles.
- **φ = 90 and d = λ/4:** This setting adjusts the phase difference to 90 degrees and the dipoles are separated by a quarter-wavelength (d = λ/4), offering an interesting configuration with more complex radiation characteristics.

#### Multiple-Dipole Cases: Association de Plusieurs Antennes (Association of n Antennas)

This section allows users to analyze the radiation patterns of arrays with more than two dipoles, facilitating the study of how multiple elements influence the overall radiation pattern. Multiple dipoles can be configured with varying phase gradients and element spacings to explore their effects on directivity, beamwidth, and side lobes.


##### Input Parameters:
- **Number of Antennas (n):** Set to **6**, allowing the user to design a phased array with six dipoles.
- **Distance between Elements (d/λ):** Set to **0.4**, a fixed separation between the dipoles.
- **Phase Difference (φ):** Set to **-144** degrees, but can be varied for different configurations.

##### Buttons:
- **Tracer (Plot):** Generate the radiation pattern for the specified multiple-dipole configuration.
- **Cas Spéciaux (Special Cases):** Open a menu with predefined special cases for multiple antennas.

#### Special Cases Menu (for Multiple Antennas):
**Title:** Association of n Antennas; Special Cases.
<p align="center"><img src="https://user-images.githubusercontent.com/52040368/169894018-e4c2b14e-0ae2-4413-bfab-30b2bc6fafc8.png"></p>
1. **Alignment with Transverse Radiation (φ = 0):** This configuration aligns the elements so they radiate with a phase difference of 0, leading to uniform and symmetric radiation in the transverse direction.
   
2. **Positive Phase Gradient (φ = 129):** This setup introduces a positive phase gradient across the antenna array, which causes the beam to tilt in one direction (typically resulting in a steered beam).
   
3. **Negative Phase Gradient (φ = -129):** A negative phase gradient leads to beam steering in the opposite direction, demonstrating the flexibility of phased arrays in beamforming.

4. **Alignment with Longitudinal Radiation (φ = -2π * d/λ):** The phase difference is set based on the distance between elements and the wavelength ratio, d/λ. When **d/λ = 0.4**, this configuration produces a pattern that aligns with the longitudinal radiation axis, which is a more complex pattern showing beam steering and varying sidelobes.

5. **Alignment with Longitudinal Radiation (φ = -2π * d/λ) & Following Predefined d/λ:** This option adjusts the phase shift according to the user-defined distance between the dipoles (d/λ), allowing users to explore a range of longitudinal radiation patterns based on different element spacings.

#### Interactive Features:

- **Real-time Plot Updates:** As the user adjusts parameters like phase and distance between elements, the radiation pattern is dynamically updated, providing instant feedback on how these changes affect the overall radiation characteristics.
  
- **Advanced Analysis:** In addition to visualising the radiation patterns, the GUI provides detailed analysis of the beamwidth, directivity, and side lobe levels for each configuration, helping users assess the effectiveness of different antenna array designs.






## Results and Visualisation

The GUI provides visualisations of the radiation patterns for both individual dipole antennas and antenna arrays. The radiation patterns are displayed in polar plots, providing a clear representation of the antenna's directivity and gain in different directions.

The GUI also provides numerical outputs such as the calculated HPBW for dipole antennas. This information can be used to analyse and compare the performance of different antenna designs.

## Applications

This MATLAB GUI is a valuable tool for a variety of applications, including:

* **Antenna Design and Analysis:** The GUI provides a user-friendly interface for designing and analysing dipole antennas and phased arrays.
* **Educational Purposes:** The GUI can be used as a teaching tool to illustrate the fundamental principles of antenna theory and radiation patterns.
* **Research and Development:** The GUI can be used to explore different antenna configurations and optimise their performance for specific applications.

## Examples

The GUI includes several pre-defined examples that showcase the capabilities of the software. These examples may include:

* **Directive Antenna with a sinc(5θ) radiation pattern**
* **Short Dipole**
* **Half-Wave Dipole**
* **Full-Wave Dipole**

## Project Demonstration

A video demonstration of the project is available on YouTube: [YouTube Video](https://www.youtube.com/watch?v=FCVu-16SsCk).

The video covers the following:

* **Dipole Antenna Analysis:** Demonstrates the visualisation of different dipole types, including short, half-wave, full-wave, and variable-length dipoles.
* **Antenna Array Analysis:** Demonstrates the interactive adjustments of phased antenna array parameters, such as the number of elements, distances, and phase gradients.
* **Key Metrics:** Explains key antenna metrics such as HPBW and phase patterns for ionospheric reflection.

## About the Project

This project was developed by **Nabil Salhi**. It leverages MATLAB to provide a visual and interactive platform for understanding the behavior of dipole antennas and phased array antennas. Designed for engineers, enthusiasts, and students, the project aims to enhance the understanding of antenna systems, phased arrays, and the fundamentals of antenna design.

- **Developer:** Nabil SALHI
- **Contact:** [salhinabilpro@gmail.com](mailto:salhinabilpro@gmail.com)
- **Created:** 2013, during the preparation for the State Engineer degree at Sidi Mohammed Ben Abdellah University, Fez
- **Updated:** 2022, for publication
<p align="center">
<img src="https://user-images.githubusercontent.com/52040368/169894012-6a7b776e-e7ed-46af-b124-f7b128c26759.png">
</p>

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgements

* **MATLAB:** The project was developed using MATLAB, a powerful software for numerical computing and visualisation.
* **Nabil Salhi:** The developer and maintainer of this project.

## Resources and Links

* **Project Repository:** [GitHub Repository](https://github.com/salhina/dipole-antenna-matlab)
* **Project Website:** [Project Website](https://salhina.github.io/)
* **Explainer Video:** [YouTube Video](https://www.youtube.com/watch?v=FCVu-16SsCk)      

---
## Connect

[![Portfolio](https://img.shields.io/badge/GitHub-Portfolio-blue?logo=github)](https://salhina.github.io/)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-blue?logo=linkedin)](https://www.linkedin.com/in/nabil-salhi)
[![Email](https://img.shields.io/badge/Email-Contact-blue?logo=gmail)](mailto:salhinabilpro@gmail.com)

## Stay Updated

* Star the repository on GitHub to show your support and stay updated on new releases and features.
