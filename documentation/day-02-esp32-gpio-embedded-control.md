# Day 2 — ESP32, GPIO & Embedded Control

## Overview

Day 2 continued the technical foundation of the Robotic Lunar Rover project by moving from basic electronics into embedded control.

The focus was on understanding how the ESP32 communicates with electronic components and how simple software instructions can produce physical outputs.

## Understanding the ESP32

The ESP32 was explored as the microcontroller at the centre of the embedded system.

We looked at:

- Microcontroller architecture
- GPIO pins
- Digital and analog signals
- INPUT and OUTPUT modes
- The relationship between the microcontroller and external components

This helped establish how the ESP32 could later be used to interface with sensors and control rover hardware.

## Embedded Programming

The day introduced the basic structure of an embedded program using:

- `setup()`
- `loop()`
- `pinMode()`
- `digitalWrite()`

The distinction between configuring a pin and controlling its output was an important part of the session.

## Building the Circuit

The ESP32 was connected to a breadboard circuit containing an LED and a resistor.

The work involved understanding:

- GPIO connections
- Power and ground
- LED polarity
- Current-limiting resistance
- Breadboard connections

The circuit provided a simple physical system for testing the ESP32's digital output.

## Practical Circuit Progression

The practical work progressed through several stages as the LED circuit was developed and connected to the ESP32.

### Start — Initial LED Circuit

Two LEDs were initially set up on the breadboard as part of the circuit-building process.

![Initial LED circuit](../DAY%202%20S.jpg)

*Initial LED circuit setup.*

### Middle — Adding Resistors

Resistors were then incorporated into the LED circuit as part of the circuit implementation.

![LED circuit with resistors](../DAY%202%20M.jpg)

*LED circuit with resistors.*

### End — Connecting the ESP32

The completed circuit was connected to the ESP32, providing the hardware setup for testing GPIO-based control.

![LED circuit connected to ESP32](../DAY%202%20E.jpg)

*LED circuit connected to the ESP32.*

## From Code to Physical Output

A GPIO pin was configured as an output and used to control the LED.

This demonstrated the basic embedded-systems flow:

**Program → ESP32 GPIO → Circuit → Physical Output**

The circuit was compiled, uploaded to the ESP32, and tested.

## Debugging & Troubleshooting

The session also demonstrated that embedded development involves both software and hardware debugging.

Issues and checks included:

- Circuit connections
- LED polarity
- GPIO configuration
- ESP32 connections
- USB communication
- COM-port selection
- Flashing/upload problems

Troubleshooting these issues helped connect programming concepts with real hardware behaviour.

## Connecting This to the Rover

Although the activity used a simple LED circuit, the underlying concept is directly relevant to rover development.

The same principle of using the ESP32 to control physical outputs would later be extended to components such as motor drivers and motors.

This established the foundation for progressing from simple GPIO control toward actual rover movement and control.

## What I Learned

Day 2 helped me understand how an ESP32 can act as the interface between software and physical electronics.

I learned about GPIO configuration, basic embedded-programming structure, digital outputs, circuit interfacing, and hardware/software troubleshooting.

The session showed how even a simple LED circuit can demonstrate the fundamental control architecture that is later used in a more complex robotic system.

---

### Program

**ATLAS Summer Tech School 2026**  
**Robotic Rover Program**

*This project documentation is being developed progressively as I document the technical stages of the rover project.*
