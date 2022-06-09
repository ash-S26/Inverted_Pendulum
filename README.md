# Inverted-Pendulum
Aim is to stabilzse pendulum using PID and LQR controller

## PID Control 

PID control was used to stabilize the inverted pendulum in upright position. The drawback behind PID was that it was giving force that was much above physical limit due to which cart contineously moves in direction of force for longer period of time seen in below results :-

![](https://i.imgur.com/AD1bufn.png)

![](https://i.imgur.com/8mvxrjP.png)

![](https://i.imgur.com/SAmLpDJ.png)

## LQR Control 
After seeing drawback in PID controller we moved to LQR controller to stabilize the pendulum in upright position. We tunned the Q (penalty on states) and R (penalty on actuators) matrix to obtain the desired results within some physical limits. Below plots shows variation of theta, force and postion(x) with time. In animation we can see pendulum stabilize in upright postion at desired (x=5). p

![](https://i.imgur.com/ngM1cxZ.png)

![](https://i.imgur.com/xl6qyeq.gif)


