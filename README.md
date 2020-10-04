# Aerial-Robotics

This repository contains the programming files for the course on Aerial Robotics offered 
by the Penn University. It includes 1D, 2D and 3D Linear Controller for a quadrotor.

The instructions on using different files in given in the file *Problem Statement* present
inside each folder.

Currently, it contains 1D and 2D linear controllers. By 15 October, 2020 it will host,
3D Linear controller and a non-linear controller as well. A simulink model will be uploaded
shortly for simulating the dynamics of the quadrotor.

Note that mathematical knowledge in the following topics will be of help:
1. Linear Algebra
2. Differential Equations
3. Calculus of Variations


###Folder Structure
Under each folder, *controller.m* script contains the control laws used to drive the quadrotor.
*runsim.m* file contains instructions to link files from the /utils directory and run simulations
for the control law entered in the *controller.m* script.
