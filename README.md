# Line Follower Robot with Junction Counter
### Built Using Purely Discrete Digital Logic (No Microcontroller)

## Overview
A fully autonomous line-following robot capable of counting junctions 
and stopping at a pre-programmed junction number — implemented entirely 
using discrete digital ICs (AND, OR, NOT gates and a CD4017 decade 
counter). No microcontroller or software was used at any stage.

## The Core Challenge
Most line-follower robots offload decision-making to a microcontroller. 
This project implements all navigation and counting logic directly in 
hardware — forcing a deep understanding of combinational and sequential 
digital circuits at the gate level.

## ICs Used
- AND, OR, NOT gates — for sensor-based directional logic
- CD4017 Decade Counter — for junction counting and stop logic

## How It Works
1. IR sensors detect the line and feed signals into the gate logic
2. AND/OR/NOT combinations drive left/right motor decisions
3. Each junction triggers a clock pulse to the CD4017
4. At the pre-set count, the output pin of CD4017 cuts motor power

## Files
| File | Description |
|------|-------------|
| `simulation/line_follower.pdsprj` | Proteus simulation file |
| `schematics/schematic.pdf` | Full circuit schematic |
| `report/DLD_Project_Report.pdf` | Semester project report |
| `Demo.mp4` | Demo Video of Bot |
## Tools Used
- Proteus Design Suite (simulation & schematic)
- Discrete digital ICs (hardware implementation)

## Context
Semester project for Digital Logic Design (DLD) course  
BE Mechatronics Engineering — NUST, 2026 Line-follower-junction-counter-digitalIC
