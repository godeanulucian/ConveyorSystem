# ConveyorSystem

• Presentation
Two conveyor belts (1 and 2) bring materials that must be transferred to two exit belts (3 and 4). An 
intersection point has been designed into the system so that materials from any of the input lanes can 
be transferred to any of the output lanes. Each of the bands can be turned on individually. The 
operating status of the strips is indicated by the P1, P2, P3 and P4 marking lamps. All bands must be 
stopped simultaneously when pressing the S0 button; The input lanes must be stopped simultaneously 
when the S5 button is pressed.

• Functional description 1
Only one of the input lanes can work and only if the corresponding output lane (depending on the 
position of the selection flap at the intersection point) is switched on. The valve position is 
simulated by the corresponding switching of switches S6, S7 and S8

• Functional description 2
Unlike the behavior from functional description 1, both input bands can be turned on simultaneously, if the 
position of the selector valve allows (S7 - middle) and if the output bands are also simultaneously turned on. 
In addition, due to the environment in which the system operates, it is assumed that the valve position can 
sometimes be incorrectly determined (sensors blocked by impurities) and therefore the condition of the valve 
must be monitored: if 2 sensors are activated simultaneously, the system stops and an alarm sounds for 5 
seconds .