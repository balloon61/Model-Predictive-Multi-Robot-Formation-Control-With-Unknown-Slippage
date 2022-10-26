# Multi-robot-formation-control-with-unknown-slippage

## Description 
This package implement multi-robot formation control with Receding-Horizontal scheme and the adaptive control to overcome the unknown slippage, the unknown slippage is an important issue when robot is moving outdoor for example in different type of soil.
This pacjage mainly follow two papers (1) Observer-Based Adaptive Tracking Control of Wheeled
Mobile Robots with Unknown Slippage Parameters (2) Leader-Follower Formation Control of Multiple Non-
holonomic Mobile Robots Incorporating a Receding-
Horizon Scheme
Know that the report is a rewrite version of these two select papers.
## Requirement
Matlab, simulink, Mobile Robotics Simulation Toolbox

## Step

### Adaptive control only
AdaptiveControlTrajectoryTracking.slx
This simulink file can track circle trajectory and linear trajectory with adaptive control.

### Formation control and Adative control
Adaptive_and_Formation_control_main.slx
This simulink file uses adaptive control for the leader, on the other hand the formation will change in 60 sec.

## Demo
This simulation is divide by three videos.

(1) https://youtu.be/acIaePsJlAY
(2) https://youtu.be/s1IC-PTa-eM
(3) https://youtu.be/5PbcEr_12_w


