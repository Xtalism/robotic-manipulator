# Robotic Manipulator

This is a simple MATLAB App Designer application interface to manipulate manually or digitally a Robotic Manipulator Hand.

This Robotic Manipulator has six degrees of freedom. Its behaviour was analyzed with Denavit-Hartenberg Parameters.

## Table of Contents
- [Robotic Manipulator](#robotic-manipulator)
  - [Table of Contents](#table-of-contents)
  - [Project Description](#project-description)
  - [Hardware Used](#hardware-used)
  - [Wiring](#wiring)
  - [Software Requirements](#software-requirements)
  - [Prerequisites](#prerequisites)
  - [Installation Instructions](#installation-instructions)
  - [Usage](#usage)
  - [Features](#features)
  - [License](#license)
  - [Contact Information](#contact-information)
  - [Acknowledgements](#acknowledgements)

## Project Description
This project aims to provide an intuitive interface for controlling a robotic manipulator with six degrees of freedom. The interface allows for both manual and digital manipulation, making it versatile for various applications.

<p align="center">
  <img width="auto" height="auto" src="img/structure.png">
</p>

## Hardware Used
<ul>
    <li>Arduino Uno</li>
    <li>Six Servomotors MG996R</li>
    <li>Voltage Power Supply: 7.2V and 2A</li>
    <li>Three Joysticks</li>
</ul>

## Wiring

<p align="center">
  <img width="auto" height="auto" src="img/pictoric.png">
</p>

<p align="center">
  <img width="auto" height="auto" src="img/schematics.jpg">
</p>

## Software Requirements
  - [MATLAB](https://la.mathworks.com/products/matlab.html)
  - [MATLAB Support Package for Arduino Hardware](https://la.mathworks.com/matlabcentral/fileexchange/47522-matlab-support-package-for-arduino-hardware)
  - [MATLAB App Designer](https://la.mathworks.com/products/matlab/app-designer.html)

## Prerequisites
- MATLAB R2020a or later

## Installation Instructions
1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/robotic-manipulator.git
    ```
2. Open MATLAB and navigate to the cloned repository.
3. Install the required MATLAB support packages:
    - <a href="https://la.mathworks.com/matlabcentral/fileexchange/47522-matlab-support-package-for-arduino-hardware" target="_blank">MATLAB Support Package for Arduino Hardware</a>
    - <a href="https://la.mathworks.com/products/matlab/app-designer.html" target="_blank">MATLAB App Designer</a>

## Usage
1. Connect the Arduino Uno and the servomotors as per the hardware setup.
2. Open the MATLAB App Designer and load the project.
3. Change the 'COM' and 'Arduino' values to match yours.
4. Run the application and use the interface to control the robotic manipulator.

<p align="center">
  <img width="auto" height="auto" src="img/interface.png">
</p>

## Features
- Manual and digital manipulation of the robotic arm
- Real-time control via MATLAB interface
- Easy setup and configuration

<!-- ## Contributing
Contributions are welcome! Please read the [contributing guidelines](CONTRIBUTING.md) first. -->

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact Information
For any questions or suggestions, please contact [manuel.pina.olivas@gmail.com](mailto:manuel.pina.olivas@gmail.com).

## Acknowledgements
- [MATLAB Central](https://www.mathworks.com/matlabcentral)
- [Arduino](https://www.arduino.cc/)