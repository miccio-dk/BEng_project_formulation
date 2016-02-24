# UAVCAN-enabled indoor positioning solution for unmanned veicles


## Synopsis
The project aims to develop an indoor positioning system for aerial unmanned veicles (UAVs) based on the decaWave DW1000 Module.
These devices can perform point-to-point ranging using time difference of arrival (TDOA) and time of flight (TOF) schemes.
From these data, a triangolation algorithm shall be devised and implemented, in order to provide the UAV position in a 2D coordinate system.

The complete system is composed of one (or more) "tags" and 3 (or 4, for 3D positioning) "anchors". 
Each device shall include a DW1000 Module and a microcontroller, which will perform the position estimation.

In order to ease development, tags and anchors will share the same hardware platform, composed of the aforementioned plus a power supply unit and the rrequired communication ports.

The tag shall interface with its host through UAVCAN - a community-driven effort for standardizing communication across drone peripherals - and broadcast information about the veicle location. 
A message definition shall be choosen amongst UAVCAN pool of standard definition, or devised from scratch.

The project shall cover aspects of both hardware (i.e. design for manufacturability, power efficiency) and software (embedded programming, localization algorithm) development and shall be carried out with the cooperation from UAVComponents APS.


## Project
 - Individual project
 - 15 ECTS credits


## Product requirements
 - Accuracy: 10 cm
 - Range: 250 m @ lowest data rate
 - Power consumption: 
   - Idle: max 30 mA 
   - Tx/Rx: max 200 mA 
 - Connectivity: USB, UAVCAN


## Milestone plan
 - [ ] get the modules to work (Arduino, mbed)
   - [ ] simple tx/rx
   - [ ] ranging
   - [ ] localization
 - [ ] schematics design
 - [ ] software development
   - [ ] implement basic peripherals
   - [ ] port working localization code to ARM
   - [ ] integrate libUAVCAN 
 - [ ] integration and validation tests
 - [ ] documentation 
   - [ ] final report
   - [ ] product datasheet
   - [ ] production files

