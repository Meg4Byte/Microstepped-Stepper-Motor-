# Stepper Motor Simulation with Microstepping in MicroCap12

Simulation of a two phase stepper motor in MicroCap-12  

<p align="center">
  <img src="https://github.com/Meg4Byte/Stepper-Motor-Simulation/assets/121357383/4b961d33-7b76-4248-8d65-e1425d1683c8">
</p>

## Table of Contents

- [Project Description](#project-description)
- [Features](#features)
- [Stepper Motor Macro Model](#stepper-motor-macro-model)
- [Installation Instructions](#installation-instructions)
- [Usage Instructions](#usage-instructions)
   - [Open the Project](#open-the-project)
   - [Run the Simulation](#run-the-simulation)
- [Waveforms](#waveforms)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)
  
## Project Description

This project simulates a two-phase stepper motor with microstepping using MicroCap12. It aims to demonstrate the control of a stepper motor with microstepping, visualize output signals on waveforms, and provide an accurate model of a stepper motor. The project is designed to offer hands-on experience for those interested in control theory and how does stepper motor achieve such small angles.

## Features

- Control stepper motor with microstepping
- Visualize microstepping signals
- Display output signals: motor acceleration, velocity, torque, and angle
- Input signals: sine and cosine voltages for microstepping
- Accurate simulation model of a stepper motor

## Stepper Motor Macro Model

<p align="center">

  <img src="https://github.com/Meg4Byte/Stepper-Motor-Simulation/assets/121357383/0eabb931-155e-46fb-a5a2-9f9751ef8f10)">
</p>

A stepper motor macro model is a simplified representation of a stepper motor's behavior and characteristics. It captures the essential dynamics of the motor, such as step angle, torque, velocity enabling efficient simulation and analysis. This model helps in understanding how the motor responds to different input signals, particularly in applications requiring precise control of position and speed.

## Installation Instructions

1. **Install MicroCap12:**
   - Download and install MicroCap12 from MicroCap's official website

2. **Clone the Repository:**
   ```bash
   git clone https://github.com/Meg4Byte/Stepper-Motor-Simulation.git

## Usage Instructions

 #### Open the Project:
   - Launch MicroCap12 , click on the open project icon in top left corner and open the project file .

 #### Run the Simulation:
   - Click on the 'Analysis' button to start the transient analysis.
   - Observe the output waveforms for motor acceleration, velocity, torque, and angle.
   - Change in control signals , add load and observe the output.

## Waveforms

<details> 

  <summary><h2> Input signals and output Torque/Velocity/Acceleration  </h2></summary>

  - Input Phases
    
  ![input_phases](https://github.com/Meg4Byte/Stepper-Motor-Simulation/assets/121357383/b40c2dbe-dbff-4007-80c4-fbe604bc5304)

  **Summary:** This image shows the microstepped sine and cosine input signals provided to the stepper motor. The signals are represented by the yellow and purple waveforms, which are phase-shifted by 90 degrees. The microstepping technique divides each step into smaller steps to achieve smoother motion and higher resolution.

  - Velocity
    
  ![veloc](https://github.com/Meg4Byte/Stepper-Motor-Simulation/assets/121357383/9be0203d-021d-443e-b4f1-ad7e79ef76eb)

**Summary:** This image focuses on the stepper motor's velocity output. The red waveform indicates the changes in velocity over time. This detailed view helps in analyzing the motor's speed characteristics and how well it maintains a steady state under microstepping control.

  - Acceleration , velocity and torque
    
  ![acc_vel_torq](https://github.com/Meg4Byte/Stepper-Motor-Simulation/assets/121357383/ffb8186b-9269-4274-884e-e28d8bfc6fe6)

**Summary:** This image depicts the stepper motor's output signals for acceleration , velocity and torque,. The top graph shows the acceleration, the middle graph displays the velocity, and the bottom graph represents the torque. These outputs are a result of the microstepped input signals and provide insight into the motor's dynamic performance.

<!--END_SECTION:activity-->

</details>


## Contributing

 - If you'd like to contribute to this project, please follow these guidelines:
 
 - Fork the repository on GitHub
 
 - Clone your forked repository to your local machine
 
 - Create a new branch for your feature or bug fix
 
 - Make your changes and commit them
 
 - Push your changes to your fork on GitHub
 
 - Create a pull request to submit your contribution
 
## License 

This project is licensed under the MIT License. You are free to use, modify, and distribute this code at your own discretion.

## Contact

For questions or feedback, feel free to reach out at petnenadd_d@uns.ac.rs .

