# Projectile motion simulator
A flight simulator that models and visualizes 2d projectile motion, comparing an ideal trajectory against a real trajectory (which takes into account air resistance in a laminar regime).

## Features
*  User input: initial velocity, launch angle, mass and resistance coefficient
*  Safety checks: includes validation to prevent 90-degree launch
*  Comparative plotting: Generates clear graphs to visualize the impact of friction on the bullet's motion

## Mathematical model
* Ideal trajectory: uses kinematics parabolic equations
* Real trajectory: incorporates a viscous friction force proportional to velocity (according to Stokes' law).

*NOTE: In this approach, terminal velocity and buoyant force are neglected*

## Technologies used
* Python 3
* Numpy
* Matplotlib
