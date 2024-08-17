# Robotic Manipulator

This is a simple MATLAB App Designer application interface to manipulate manually or digitally a Robotic Manipulator Hand.

This Robotic Manipulator has six degrees of freedom. Its behaviour was analized with Denavit-Hartenberg Parameters.

## Hardware Used
<ul>
    <li>Arduino Uno</li>
    <li>Six Servomotors MG996R</li>
    <li>Voltage Power Supply: 7.2V and 2A</li>
    <li>Three Joysticks</li>
</ul>

## Software Requirements
I installed the [MATLAB Support Package for Arduino Hardware](https://la.mathworks.com/matlabcentral/fileexchange/47522-matlab-support-package-for-arduino-hardware) to program with the Arduino Uno and I also used [MATLAB App Designer](https://la.mathworks.com/products/matlab/app-designer.html) to build an user interface.

## Installation Instructions
1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/robotic-manipulator.git
    ```
2. Open MATLAB and navigate to the cloned repository.
3. Install the required MATLAB support packages:
    - [MATLAB Support Package for Arduino Hardware](https://la.mathworks.com/matlabcentral/fileexchange/47522-matlab-support-package-for-arduino-hardware)
    - [MATLAB App Designer](https://la.mathworks.com/products/matlab/app-designer.html)

## Usage
1. Connect the Arduino Uno and the servomotors as per the hardware setup.
2. Open the MATLAB App Designer and load the project.
3. Change the 'COM' and 'Arduino' values to match yours.
4. Run the application and use the interface to control the robotic manipulator.

<p align="center">
  <img width="auto" height="auto" src="img/interface.png">
</p>

## Contributing
Contributions are welcome! Please read the [contributing guidelines](CONTRIBUTING.md) first.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact Information
For any questions or suggestions, please contact [your email](mailto:youremail@example.com).