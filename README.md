Title: ReadMe.md
- Created: Louis Ahumada Medina
- Date: 10.24.2024

Description:
This repo contains all the files and documentation needed to build a USB-C to UART 2.0 PCB. 
The USB-C is connected to header pins for the UART communication. 
LEDs will indicate, will blink, when the UART communication is actively occurring.

![Front_PCB_Image](https://github.com/user-attachments/assets/214ae2f0-af2e-4884-b6e0-34f0f2260328)

![Back_PCB_Image](https://github.com/user-attachments/assets/ba378146-53e5-4e52-8f3d-3d59f379a915)

Features:
- QR-Code that links to this repository
- USB-C to UART 2.0
- LED indicator when UART is active
- Hand Solderable

Usage Rights:
- MIT License

Design Software:
- KiCAD 8.0

How to Use:
- Every version folder will contain all files and dependencies needed for PCB.
  - Project File
  - PCB File
  - Schematic File
  - Dependency Files
  - Board Overview PDF
  - 3D Models
  - Footprints
  - Templates
 
- Step 1: Verify that KiCAD 6 or higher is working
- Step 2: Download the desired folder version
- Step 3: Unzip folder and subfolders
- Step 4: Open the "Tech Demo ECE 441" Folder
- Step 5: Open the "Tech Demo ECE 444.kicad_pro" file to start the project
- Note: Make sure the project dependencies (ei. 3dmodels) are mapped to the correct file location

Versions:

- V1.0
  - Initial Draft PCB and Schematic Layout
  - Not Validated
  - QR-Code nonoperational
  - Prototype PCB
 
- V2.0
  - Rewired Schematic
  - Made PCB Smaller
  - Rewired PCB traces
  - Revered LEDs
  - Replaced QR-Code with one that links to this repo
  - Prototype PCB     
