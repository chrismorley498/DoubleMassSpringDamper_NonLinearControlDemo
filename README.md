# DoubleMassSpringDamper_NonLinearControlDemo
This repo contains simulink (Simscape Multibody) models of MIMO systems where adaptive and robust control laws are demonstrated. Derivation of control laws are also provided in folder named controlLawDerivations

## Robust Control
Open the Simulink Model titled doubleMassSpringDamper_SlidingRobustControl.slx
This model can be run immediately without any changes needed. Double clicking on the disturbance generator block will open up a window where you can modify the amplitude and frequency of the disturbances acting on mass 1 & 2 seperately.
This control law has been designed to guarantee convergence of the trajectory to the desired trajectory when the external disturbances are up to 200N in force. You can experiment and see how large you can make the disturbance before mass 1 & 2 can no longer follow their desired trajectories.
The desired trajectories can be modified by changing the contents of the highlighted areas named Trajectory Mass 1 & 2 respectively. 
Data Inspector or scope can be used to view the resulting tarjectories againts the desired ones

## Adaptive Control
Open the Simulink Model titled doubleMassSpringDamper_SlidingAdaptiveControl.slx
This model can be run immediately without changes. Double click the block titled "Mass Spring Damper" to change the masses if desired. You can observe how the control law if effective across a large range of masses.
The desired trajectories can be modified by changing the contents of the highlighted areas named Trajectory Mass 1 & 2 respectively. 
Data Inspector or scope can be used to view the resulting tarjectories againts the desired ones
