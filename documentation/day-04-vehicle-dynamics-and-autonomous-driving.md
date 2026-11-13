# Day 4 — Vehicle Dynamics & Autonomous Driving

## Overview

Day 4 of the ATLAS Summer Tech School 2026 focused on understanding the mechanical principles and control systems involved in autonomous robotics.

The session explored different rover control modes, motor drivers, locomotion, sensors, and the relationship between mechanical movement and electronic control.

![Day 4 — Vehicle Dynamics & Autonomous Driving](../DAY%204.png)

*Day 4 — Vehicle Dynamics & Autonomous Driving programme overview.*

## Rover Control Systems

The instructor introduced different ways in which the Lunar Rover could operate.

The main control modes discussed included:

- Remote control using a smartphone.
- Autonomous operation without continuous human control.
- Hybrid operation combining remote control and basic autonomous capabilities.

The ESP32 was introduced as the central controller that could support wireless communication between the rover and a mobile device.

The session also explained the difference between human-in-the-loop and fully autonomous robotic systems.

![Day 4 — Vehicle Dynamics & Autonomous Driving](../DAY%204.1.png)

## Motor Drivers & Electronics

The session introduced the role of motor drivers in controlling the rover's DC motors.

Topics discussed included:

- L298 motor driver.
- Comparison between L298 and L293D.
- Motor driver integration with the microcontroller.
- Breadboard prototyping.
- Safe wiring and circuit connections.

The instructor explained why selecting suitable electronic components requires understanding their underlying electrical and engineering principles.

## Locomotion & Mechanical Principles

An important part of the session focused on how a robot produces movement.

Concepts discussed included:

- Degrees of Freedom (DOF).
- Linear and rotary motion.
- Conversion of motor rotation into rover movement.
- Mechanical joints.
- Kinematics and dynamics.

The distinction between kinematics, which studies motion, and dynamics, which considers the forces associated with motion, was also introduced.

## Sensors & Actuators

The instructor explained the difference between sensors and actuators within a robotic system.

Examples discussed included:

- LDR for light detection.
- Humidity sensors.
- Touch and switch sensors.
- Buzzer for sound indication.
- DC motors for movement.
- Other output components such as displays and a laser module.

The ESP32 was introduced as the controller connecting the sensor inputs and actuator outputs.

## Sense–Plan–Act Architecture

The session introduced a fundamental robotics control process:

**Sense → Plan → Execute (Act)**

This describes how a robotic system:

1. Collects environmental information through sensors.
2. Processes the information through its controller.
3. Produces an action through its actuators.

This concept helped explain how the rover's electronic and mechanical components work together as a coordinated system.

## Rover Chassis & Mechanical Design

The instructor discussed the physical structure and material selection of the workshop rover.

Topics included:

- MDF (Medium Density Fiberboard) chassis.
- A chassis length of approximately 30 cm.
- Mechanical joints and structural components.
- Integration of motors and sensors.
- The importance of mechanical design in rover movement.

The instructor also explained that the workshop used a pre-designed and pre-cut chassis so that the programme could focus on assembly, control systems, automation, and electronics.

## Transition to Motor Interfacing

The session concluded with a transition from theoretical concepts toward practical motor interfacing.

The instructor directed the class to begin working on connecting and controlling the rover's motors.

This marked the next stage in progressing from understanding the rover's control architecture toward implementing its movement system.

## What I Learned

Day 4 helped me understand how mechanical movement, electronics, and control systems come together in robotics.

I learned about different rover control modes, the role of motor drivers, the principles of locomotion, and the relationship between sensors, controllers, and actuators.

The session also introduced the Sense–Plan–Act architecture and helped me understand how a robotic system processes information and translates it into physical movement.
