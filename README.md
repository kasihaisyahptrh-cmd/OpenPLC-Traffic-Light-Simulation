# OpenPLC-Traffic-Light-Simulation
OpenPLC Ladder Logic traffic light simulation with 5s red, 2s yellow, and 5s green timing sequence.

# Traffic Light Simulation Using OpenPLC

A Traffic Light Simulation developed using OpenPLC Ladder Logic to demonstrate a sequential traffic light control system using timer-based logic.

## System Operation

The traffic light operates continuously with the following timing sequence:

| Light | Duration |
|---|---:|
| Red | 5 seconds |
| Yellow | 2 seconds |
| Green | 5 seconds |

The sequence repeats continuously during system operation.

## Control Sequence

Red Light (5 s)
↓
Yellow Light (2 s)
↓
Green Light (5 s)
↓
Repeat

## Software

- OpenPLC Editor
- Ladder Logic (LD)

## Learning Objectives

- Understanding sequential control using PLC Ladder Logic
- Implementing timer-based control
- Understanding PLC timers
- Developing basic industrial automation logic
- Practicing sequential output control

## Project Description

This project simulates a basic traffic light control system using OpenPLC Ladder Logic. Timers are used to control the duration of each traffic light state. The red light remains active for 5 seconds, followed by the yellow light for 2 seconds, and the green light for 5 seconds. After the green-light sequence is completed, the system automatically returns to the red-light state and continuously repeats the sequence.

