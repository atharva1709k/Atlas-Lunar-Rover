# Day 5 — Rover Control Architecture & Engineering Constraints

## Overview

Day 5 of the ATLAS Summer Tech School 2026 focused on understanding the control architecture and engineering constraints involved in the Robotic Lunar Rover project.

The session explored different rover control modes, motor drivers, locomotion, sensors, and the relationship between electronic control and mechanical movement.

## Control Architecture

The instructor described three operating approaches:

- **Remote control:** a smartphone communicates with the rover through the ESP32 for operator-directed movement.
- **Autonomous operation:** the rover performs basic actions without continuous phone input.
- **Hybrid operation:** remote control and basic autonomous behaviour coexist.

The recording characterises the workshop rover as a **human-in-the-loop hybrid system**, not a fully AI/ML-driven autonomous robot. Remote command capability was also discussed as a fallback if autonomous routines stop responding.

## Motor Driver and Locomotion

The **L298 motor driver** was identified as the motor-driver choice and contrasted with the L293D. The session emphasised that component selection should be understood through engineering principles rather than treated as an arbitrary kit choice.

The rover's DC motors produce rotary motion. At the vehicle level, this produces linear movement of the chassis. The lecture also introduced degrees of freedom and distinguished:

- **Kinematics:** describing motion without analysing the forces causing it.
- **Dynamics:** analysing motion together with the forces involved.

The recording refers to two mechanical joints in the rover design, but does not provide enough detail to specify their geometry or movement range.

## Sensing and Actuation

The instructor outlined a high-level **Sense → Plan → Act** model:

1. **Sensors:** examples discussed included an LDR, humidity sensor, and touch/switch sensors.
2. **Controller:** the ESP32 was described as the system's processing and control unit.
3. **Actuators and outputs:** DC motors, a buzzer, display units, and a laser module were mentioned in the hardware discussion.

The recording states that the breadboard's available space limits the planned integration to approximately three or four sensors from the kit. This is a stated design constraint, not evidence that those sensors were all installed or tested.

## Chassis and Integration Constraints

The instructor described the workshop rover chassis as a pre-cut **30 cm MDF** frame rather than a 3D-printed chassis. The lecture noted that mechanical design and material selection had been completed in advance so the workshop could focus on assembly, control systems, automation, and electrical integration.

This differs from the broader programme roadmap, which describes 3D-printed chassis design and prototyping as planned curriculum activities. The recording's specific description of the workshop build is retained here rather than assuming that every roadmap item applied to the final hardware.

## Wiring and Prototyping Safety

The session highlighted the importance of clean breadboard layouts and firmly seated jumper wires. A short circuit caused by positive and negative connections touching was cited as an example of a circuit failure.

This is a reminder that prototype wiring should be checked carefully before power is applied. The recording does not establish that this particular incident involved this project's own board.

## Session Boundary

At the end of the recording, the instructor handed the session over to begin motor interfacing. The recording ends during that transition. It does not verify that motor interfacing, firmware upload, sensor integration, or a movement test took place.

## What This Session Established

The recording supports the following technical takeaways:

- A human-in-the-loop hybrid control concept using ESP32-based remote operation alongside basic autonomous behaviour.
- L298 as the motor driver identified during the lecture.
- A Sense–Plan–Act system model connecting sensors, the ESP32, and actuators.
- Rotary-to-linear motion as the basis of wheeled rover locomotion.
- Practical constraints involving breadboard space, wiring quality, and the stated MDF chassis.

These are documented as lecture content and design context, not as claims of independently completed implementation.

---

### Programme

**ATLAS Summer Tech School 2026**  
**Robotic Rover Program**

*This repository documents the programme's technical learning stages using available recordings, project materials, and photographs. Planned activities and confirmed practical work are distinguished wherever the evidence allows.*
