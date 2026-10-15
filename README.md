# RGB LED Controller Hardware Design

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)](https://opensource.org/licenses/MIT)
[![KiCad](https://img.shields.io/badge/KiCad-FFFFFF?style=flat-square&logo=kicad&logoColor=blue)](https://www.kicad.org/)

A custom-designed printed circuit board (PCB) for an RGB LED controller, featuring full schematic capture, board layout, and manufacturing-ready fabrication files.

##  Table of Contents
- [About the Project](#about-the-project)
- [Tech Stack](#tech-stack)
- [Getting Started](#getting-started)
- [Repository Structure](#repository-structure)

##  About the Project

This project contains the complete hardware design files for a custom RGB LED controller. It serves as a physical hardware module designed to drive and manage RGB LED lighting systems.

### Tech Stack
*   **EDA Software:** KiCad (for schematic capture and PCB layout)
*   **Hardware Type:** Lighting / Power Electronics

##  Getting Started

Follow these instructions to view or modify the hardware design files locally.

### Prerequisites

*   [KiCad EDA](https://www.kicad.org/download/) to open the core project files.
*   A PDF viewer to read the exported schematics.
*   A Gerber viewer (if you only want to inspect the manufacturing layers).

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/MohamedHassanExp/RGB-LED-controller.git
2. Navigate to the project directory
   ```bash
   cd RGB-LED-controller--main
3. Open `Hardware/RGB controller.kicad_pro` project file using KiCad.

## Repository Structure

The repository is organized to separate the editable design files from the static manufacturing outputs:

*   **Design Files:**
     The Hardware/ directory contains the core KiCad project files, including the schematic (RGB controller.kicad_sch), the physical layout (RGB controller.kicad_pcb), and a PDF export of the design (RGB controller.pdf).
*    **Board Renders:**
      High-resolution 3D renders of the physical layout are available as RGB controller-front.png and RGB controller-back.png.  
*    **Manufacturing Files (Hardware/Manufacturing/):** 
      This directory contains everything a fabrication house like JLCPCB or PCBWay needs to manufacture and assemble the board:
      * **RGB controller-gerber.rar:** The compressed Gerber layers and drill files for PCB fabrication.
      * **RGB controller-BOM.csv:** The complete Bill of Materials for component sourcing and assembly.
      * **RGB controller-position.csv:** The centroid/pick-and-place data for automated SMD assembly.
