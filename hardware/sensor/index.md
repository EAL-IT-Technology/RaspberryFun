---
layout: page
title: Sensor 
---

## The circuit

The sensor circuit can either be build on a piece of veroboard or on a milled PCB.  

The components needed:
* 10k&Omega resistor (x3)
* 68&Omega resistor (Please note, that this resistor replaces the 120&Omega resistor on the schematic).
* 10k&Omega trimresistor (The blue resistor with the screw terminal)
* 100 nF capacitor
* 15 pF capacitor
* TCRT5000 lightsensor
* 8 pin IC socket 
* LM293 operation comparator

The schematic of the sensor circuit. If You chose to build the circuit on veroboard, remember to be very precise regarding connection between the different components. Please note the adjustments on the schematic.
![Sensor Schematic](pics/Sensor.png "Sensor Schematic")

The PCB handed out is outlined in the images below. Remember to face the PCB right before start soldering.

| PCB from component side | Backside of the PCB |
|:--------------------:|:---------------------------:|
|<img src="pics/IMG_20151121_172505.jpg" alt="Front side of the PCB" width="400" />|<img src="pics/IMG_20151121_172523.jpg" alt="Backside of the PCB" width="400" /> 

Be careful to mount the components right and in the right places. The result should look like the picture below.
<img src="pics/IMG_20151121_173625.jpg" alt="Components mounted on the PCB" width="400" />

How to mount the components on the PCB is outlined below. Note that blue lines means buttom layer. 
| Component placement with wires | Component placements as the PCB looks|
|:--------------------:|:---------------------------:|
|<img src="pics/IMG_20151121_173625.png" alt="Components placement" width="400" />|<img src="pics/IMG_20151121_173626.png" alt="Components placed on PCB" width="400" /> 

Note that three vias, connections between top and buttom layer, has to be added to the PCB as indicated below.
![Adding vias](pics/2WD Sensor PCB Base.png)

Test the built PCB by using the microscope and multimeter before attaching power to the circuit. After attaching power, measure whether output turns high or low when the sensor is placed below either a black or white surface.
