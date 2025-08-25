# AC-to-DC-Converter
AC to DC Converter PCB design using KiCad. Includes schematic, PCB layout, 3D render, and Gerber files.
# AC to DC Converter PCB

This repository contains the schematic, PCB layout, 3D render, and Gerber files for an **AC to DC Converter circuit** designed in **KiCad**.

## 📐 Project Overview
- **Input:** AC voltage
- **Output:** DC voltage
- **Rectification:** 4 × 1N4007 diodes
- **Filtering:** 1000 µF electrolytic capacitor
- **Load Indicator:** LED with current-limiting resistor
- **Connectors:** Screw terminals for AC input and DC output

## 📂 Repository Contents
- `Gerber_ACtoDCconverter.zip` → Complete Gerber package for fabrication
- `schematic.png` → Circuit schematic
- `pcb_layout.png` → 2D PCB layout
- `pcb_3d.png` → 3D rendered PCB view

## 🚀 How to Manufacture
1. Download `Gerber_ACtoDCconverter.zip`.
2. Upload it to your preferred PCB manufacturer (JLCPCB, PCBWay, etc.).
3. Select board options (2-layer, 1.6mm thickness, HASL finish).
4. Order your board.

## 🛠 Tools Used
- **Software:** KiCad 7/8/9
- **Design Author:** EmbedGyaan – Learn Code & Circuits

## 📜 License
This project is open-source under the MIT License (you can replace with CERN OHL if you want hardware licensing).
