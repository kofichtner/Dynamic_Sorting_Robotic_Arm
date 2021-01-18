# Dynamic Sorting Robotic Arm
Course: RBE 3001
## Overview
The objective of this lab was to implement computer
vision to detect and locate objects within the robot’s task
space. Using a camera positioned above the robot’s task space,
we applied transformation matrices to convert pixel
coordinates to positions in the task space. Then, by applying
filters we were able to detect an object’s color and size. With
the ability to identify objects by color and size, the robot could
pick up and sort objects using forward kinematic, inverse
kinematic, and inverse differential kinematic trajectory
functions developed in previous labs. We also implemented a
dynamic tracking function, a URDF simulation of the robot,
and detection of an arbitrary object.
##Results
The robot was successfully able to sort objects by color and size.

![Objects before sorting (left) and after sorting (right)](https://github.com/kofichtner/Dynamic_Sorting_Robotic_Arm/blob/master/images/Picture2.png)
