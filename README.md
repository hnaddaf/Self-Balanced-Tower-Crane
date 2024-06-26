# Self-Balanced-Tower-Crane
This research aims to present a novel design for an automatic tower crane. It was designed and simulated using SOLDWORK and controlled using MATLAB Simulink.


## Project Structure

The project repository contains the following files:

- `Main.slx`: The main Simulink model of the tower crane.
- `Main.slxc`: Compiled Simulink cache file.
- `pole_plasment.m`: MATLAB script for the pole placement controller.
- `LQR_G.m`: MATLAB script for the LQR controller.
- `Presentation.pptx`: Project presentation detailing the design and control strategies.
- `fig2.jpg`, `f3.jpg`, `f4.jpg`: Images of the crane simulations and results.

## Objectives

- Build a prototype of the self-balancing tower crane to validate the design concepts.
- Design the mechanical structure based on stress and deflection analysis using SOLIDWORKS.
- Study the state-space representation and dynamics of the crane.
- Design a position tracking system using pole placement and LQR controllers.
- Test and compare the robustness of each controller to select the most suitable one.
- Design a full state observer to estimate unmeasured states.

## Design Overview

- **Mechanical Design**: Developed using SOLIDWORKS, with stress and deflection analyses performed to ensure structural integrity.
- **Control Design**: Implemented in MATLAB and Simulink, with two control strategies (pole placement and LQR) evaluated for performance.

## How to Run the Simulations

1. **Choose a Controller**: Decide whether to use the LQR or pole placement controller.
   - For LQR: Run `LQR_G.m` in MATLAB.
   - For Pole Placement: Run `pole_plasment.m` in MATLAB.
2. **Run the Simulink Model**: Open and run `Main.slx` in Simulink after setting up the desired controller.

## Prerequisites

- MATLAB with Simulink
- Control System Toolbox for MATLAB


## License

This project is licensed under the terms of Birzeit University. All rights reserved.


