# Visual Line Following with MAMBO FLY Mini Drone

## Abstract

The following paper proposes an implementation of a visual line following drone in MATLAB / SIMULINK. 
The task is to have the Parrot MAMBO FLY Mini Drone with its embedded camera at the bottom successfully follow a predefined red line on a flat green surface at a variable flying height. 
The camera’s viewfinder is split into three artificial sensors whose position is determined automatically in accordance to the height, and constant yaw adjustments depending on the sensors’ input turn the drone to the desired direction while flying at a constant speed. 
Simulation showed that the drone could successfully maneuver any path at a low height; 
however, higher heights propose a problem to the drone’s balance. 
This technique is easy to apply to other applications, such as transportation and infrastructure.
