# Controller for Nonlinear System

This repository contains the code and files for the design of a controller for a nonlinear system consisting of a crane and two pendulums. The project involves calculating the equations of motion for the system using the Euler-Lagrange method and linearizing it using Jacobian Linearization around an equilibrium point.

The state-space representation of the linearized system is given and the conditions for controllability of the linearized system are obtained. The controllability of the system is checked for specific values of the system's parameters, and an LQR controller is designed to control the system. The response of both the linearized and original nonlinear system to initial conditions is obtained, and the stability of the closed-loop system is checked using Lyapunov’s indirect method.

Additionally, the observability of the linearized system is determined for a given set of output vectors, and an optimal Luenberger observer is obtained for each observable output vector. The response of both the linearized and original systems to initial conditions and unit step input is simulated for the observer. An output feedback controller is also designed for the smallest output vector using the LQG method and applied to the original nonlinear system.

# MATLAB Code
The MATLAB folder contains the MATLAB code developed for the project simulations.

# Instructions
To run the project on your device, follow these steps:
Load the respective MATLAB (.m ) file in the MATLAB environment

Run the file to observe the output of the files

The README.md file contains additional information on the project and the files included in this repository.
