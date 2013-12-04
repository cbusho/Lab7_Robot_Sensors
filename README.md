#Library for Lab 7 Robot Sensors
Library for reading a digital ouput of the robot sensors using the MSP430

## General Notes
Configures the robot sensors using the ADC10 system to read from the sensors
Used Pins channels A3, A4, and A5 to read from center, left, and right sensors

## Functions

- `void initSensors()`
  - Initializes ADC10 system to be able to take readings off of SMCLK and enables ADC10 interrupt 

- `unsigned int checkLeftSensor()`
  - returns ADC10MEM from channel A4
  
- `unsigned int checkRightSensor()`
  - returns ADC10MEM from channel A5  

- `unsigned int checkCenterSensor()`
  - returns ADC10MEM from channel A3
