# ATtiny85 Interactive Sound & Light Node

## Overview
A compact, custom-designed circular PCB that acts as an interactive environmental sensor node. Powered by a standard 3.3V coin cell, this standalone system utilizes an ATtiny85 microcontroller to process ambient light and audio inputs to trigger a visual LED response. 

## Key Features
* **Dual-Sensor Integration:** Features both a Light Dependent Resistor (LDR) and a condenser microphone for environmental sampling.
* **Ultra-Compact Form Factor:** Designed as a circular, low-power standalone node driven by a coin-cell battery.
* **Custom Silkscreen Design:** Incorporates custom vector graphics, branding logos, and regulatory markings directly into the PCB silkscreen layers.

## Hardware Architecture & Stack
* **Core Controller/MCU:** ATtiny85V-10P
* **Sensors:** 5mm LDR, Condenser Microphone
* **Output & Power:** 5mm Yellow LED, 3.3V Coin Cell Battery with slide switch
* **PCB Design Tool:** KiCad 

## Schematic Organization & EDA Skills
Continuing the practice of industry-standard documentation, the schematic was rigorously refactored for maximum readability:
* Transitioned from direct net-wiring to a highly modular, block-based architecture.
* Utilized global/local power flags and net labels to strictly isolate the Power, MCU, and Sensor units into distinct visual bounding boxes.

## Visual Documentation

### 3D PCB Layout (Top & Bottom)
![3D Render Top](Screenshot_2025-08-10_155829.jpg)
![3D Render Bottom](Screenshot_2025-08-10_155903.png)

### Final Organized Architecture
![Organized Schematic](Screenshot_2025-08-08_212624.png)

### Initial Draft & Routing Progression
![Initial Schematic](Screenshot_2025-08-08_205908.png)

## Repository Contents
* **`/`** - Contains the native `.kicad_sch`, `.kicad_pcb`, and 3D step files for direct examination.
