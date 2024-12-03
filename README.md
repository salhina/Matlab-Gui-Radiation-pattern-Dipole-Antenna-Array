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

## Getting Started

1. **Download the Project:** Clone or download the project repository from [GitHub Repository](https://github.com/salhina/dipole-antenna-matlab).
2. **Open the GUI:** Open the MATLAB GUI file (e.g., `main.m` or `gui.m`) in MATLAB. 
3. **Explore the Interface:** Familiarise yourself with the different sections of the GUI, including the dipole antenna analysis section, the antenna array analysis section, and the input parameters.
4. **Run Simulations:** Select the desired antenna type and configure the parameters. Click the "Run" or "Simulate" button to generate the radiation pattern.

## GUI Overview

The GUI is divided into two main sections:

### 1. Radiation Pattern of Dipole Antennas

This section allows for the analysis of individual dipole antennas. The interface includes:

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

A video demonstration of the project is available on YouTube: [YouTube Video](https://www.youtube.com/watch?v=dipole-demo).

The video covers the following:

* **Dipole Antenna Analysis:** Demonstrates the visualisation of different dipole types, including short, half-wave, full-wave, and variable-length dipoles.
* **Antenna Array Analysis:** Demonstrates the interactive adjustments of phased antenna array parameters, such as the number of elements, distances, and phase gradients.
* **Key Metrics:** Explains key antenna metrics such as HPBW and phase patterns for ionospheric reflection.

## About the Project

This project was developed by Nabil Salhi. The project leverages MATLAB to provide a visual and interactive platform for understanding the behaviour of dipole antennas and phased array antennas. It is designed for engineers, enthusiasts, and students interested in learning about antenna systems, phased arrays, and the fundamentals of antenna design.

## License

This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgements

* **MATLAB:** The project was developed using MATLAB, a powerful software for numerical computing and visualisation.
* **Nabil Salhi:** The developer and maintainer of this project.

## Resources and Links

* **Project Repository:** [GitHub Repository](https://github.com/salhina/dipole-antenna-matlab)
* **Project Website:** [Project Website](https://salhina.github.io/)
* **Explainer Video:** [YouTube Video](https://www.youtube.com/watch?v=dipole-demo)
* **Developer's Portfolio and Blog:** [Portfolio](https://salhina.github.io/)
* **Developer's LinkedIn Profile:** [LinkedIn](https://www.linkedin.com/in/nabil-salhi)

## Contact

For questions or feedback, please contact the developer at [Email Address].

## Stay Updated

* Star the repository on GitHub to show your support and stay updated on new releases and features.
