###Parking Lot

#Animation
<p align="center"> 
  <img src="Animation.gif">
</p>

##Work algorithm:
  Vehicles automatically enter the parking lot when the barrier is opened and the entry signal is green. Vehicles can exit when the corresponding barrier is open and the exit signal is green. You can link entry control with a counter so that a maximum number of vehicles in the parking lot is not exceeded.

##I/O Description
2 sensors for detecting whether the entrance barrier is down or up.
2 sensors for detecting whether the exit barrier is down or up.
2 sensors for detecting whether there is a car in front of the entrance barrier or in front of the exit barrier.
2 actuators for opening the entrance or exit barrier.
2 actuators for generating a green signal for entrance or exit.
2 actuators for generating a red signal for entrance or exit.

#Inputs/Outputs:
I0.0	IN barrier is down
I0.1	IN barrier is up
I0.2	OUT barrier is down
I0.3	OUT barrier is up
I0.4	Car is at the barrier IN
I0.5	Car is at the barrier OUT
O0.0	IN barrier up
O0.1  IN barrier down
O0.2	OUT barrier up
O0.3  OUT barrier down
O0.4	Red signal IN
O0.5	Green signal IN
O0.6 Red signal OUT
O0.7	Green signal OUT

# PLC-Projects
In this repository, I will upload the PLC ladder diagram algorithms and logics for projects, I've made over the years of me being a SIEMENS masters student.
