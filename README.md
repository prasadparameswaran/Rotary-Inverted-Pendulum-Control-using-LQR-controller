
# Rotary-Inverted-Pendulum-Control-using-LQR-controller


Design of a Linear Quadratic Regulator balance controller for the Inverted Pendulum. After manually initializing the pendulum in the upright vertical position, the balance controller moves the rotary arm to keep the pendulum in this upright position. Moreover it is capable of balancing itself, even if minor external disturbances are given.
Arduino Mega is the micro controler used.

lqr.m : LQR program in MATLAB to find the gain values (K1, 
K2, K3 and K4) by tuning the Q matrix.

invertedPendulum.ino : arduino code for controlling the pendulum. It makes use of gain values from lqr.m


# Demo

![](https://github.com/prasadparameswaran/Rotary-Inverted-Pendulum-Control-using-LQR-controller/blob/main/demo.gif)



