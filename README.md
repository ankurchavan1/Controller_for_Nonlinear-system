# Controller_for_Nonlinear-system

Tasks completed in this Project:
-In this project we calculate the equations of motion for a nonlinear system of crane and two pendulums using Euler-Lagrange method.
-As the system is non-linear, we linearize it using Jacobian Linearization around an equilibrium point. State-space representation of the linearized system is given.
-Then the conditions on M, 𝑚1, 𝑚2 ,𝑙1,𝑙2 are obtained for the linearized system to be controllable.
-For specific values of M, 𝑚1, 𝑚2 ,𝑙1,𝑙2 we checked the controllability of the system. Designed an LQR controller to control the system, 
 obtained the response of both linearized and original nonlinear system to initial conditions. 
 The stability of the close loop system is checked using Lyapunov’s indirect method.
-For given set of output vector, determined for which vectors the linearized system is observable.
-Optimal Luenberger observer is obtained for each output vector for which the system is observable and 
 simulated its response for both linearized and original systemsto initial conditions and unit step input.
-Designed an output feedback controller for the smallest output vector. 
 Used the LQG method to apply the resulting output feedback controller to the original nonlinear system.
 
 # MATLAB:
 
The MATLAB package includes the Matlab codes developed for the Project Simulations

Steps to run the project on your device:

Step 1 : Load the respective Matlab (.m ) file in the matlab environment
Step 2 : Run the file to observe the output of the files

 
