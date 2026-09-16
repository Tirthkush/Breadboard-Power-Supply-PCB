# Breadboard Power Supply PCB

A compact Breadboard Power Supply PCB designed in **KiCad** to provide regulated **5V and 3.3V outputs** from a **12V DC input**.

This is my **second PCB design project**, following my first simple pocket torch PCB. The goal of this project was to design a practical power supply that can later be used for breadboard-based electronics and embedded systems projects.

## Features

- 12V DC barrel jack input
- Regulated 5V output using LM7805
- Regulated 3.3V output using LM317
- Power ON/OFF switch
- LED power indicator
- Filtering capacitors
- Multiple output connectors
- Designed using KiCad

## Circuit Overview

The PCB accepts a 12V DC input through a barrel jack. The input is then distributed to two regulation stages:

- **LM7805** provides the regulated 5V output.
- **LM317** is configured to provide approximately 3.3V output.

Filtering capacitors are included around the power stages to help provide stable supply rails.

## Design Process

The PCB was developed completely in KiCad through the following workflow:

    Circuit Planning
          ↓
    Schematic Design
          ↓
    Component Selection
          ↓
    Footprint Assignment
          ↓
    PCB Layout
          ↓
    Component Placement
          ↓
    Routing
          ↓
    Design Rule Check
          ↓
    3D PCB Visualization

## KiCad Design

The project includes the KiCad design files:

- Schematic
- PCB layout
- Component footprints
- 3D PCB view
- Bill of Materials (BOM)
- Gerber files for future fabrication

## Repository Structure

    Breadboard-Power-Supply-PCB/
    │
    ├── README.md
    │
    ├── Schematic/
    │   └── Breadboard_Power_Supply.kicad_sch
    │
    ├── PCB/
    │   └── Breadboard_Power_Supply.kicad_pcb
    │
    ├── Gerber/
    │
    ├── BOM/
    │   └── BOM.csv
    │
    └── 3D/
        └── PCB_3D_Render.png

## Applications

The intended use of this PCB is to provide convenient power rails for:

- Breadboard prototypes
- Microcontroller projects
- Sensor modules
- Embedded systems experiments
- General electronics projects

## What I Learned

Through this project, I gained practical experience with:

- Schematic capture in KiCad
- Component selection
- Footprint assignment
- PCB component placement
- PCB routing
- Voltage regulation circuits
- Design Rule Checking (DRC)
- PCB 3D visualization
- Preparing a PCB design for future fabrication

This project helped me understand the transition from a circuit idea to a complete PCB design ready for manufacturing.

## Future Plans

The next step is to get the PCB fabricated, assemble the components, and test the actual 5V and 3.3V output rails.

Future revisions could also include:

- Reverse-polarity protection
- Input fuse/protection
- USB power outputs
- More efficient switching regulators
- Improved thermal management

## Project Status

**Schematic Design ✅**  
**PCB Layout ✅**  
**3D Design ✅**  
**Fabrication ⏳**  
**Assembly ⏳**  
**Testing ⏳**

## Author

**Tirth Kushwaha**

Electronics & Telecommunication Engineering Student

Interested in **Embedded Systems, IoT, Embedded Hardware, Robotics, and Automotive Electronics**.
