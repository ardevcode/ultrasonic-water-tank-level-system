# Ultrasonic Level Sensor with 8051 Microcontroller

This project implements an ultrasonic level sensor using an 8051 microcontroller.  
The code is written entirely in Assembly language for 8051 architecture.

## Files
- `ultrasonic_8051.asm` – Main Assembly code for the project  
- `Ultrasonic.png` – Circuit diagram for the project

## Circuit Diagram
![Circuit Diagram](Ultrasonic.png)

## Usage
- Load the code into an 8051 microcontroller.
- Use pin P3.1 as `trig` and P3.0 as `echo`.
- LCD connections:
  - RS → P2.0
  - RW → P2.1
  - Enable → P2.2
  - Data → P1

## Description
- The program reads the level from an ultrasonic sensor.
- Converts the reading to digital format.
- Displays the value on an LCD.
- Uses LED indicators on P3.6 and P3.7.
