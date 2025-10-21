# LED-Board-in-Altium-Designer
Project files for the LED board assignment, created while following the "Starting with Altium Designer" course on Udemy
# Altium Designer LED Board Project

This repository contains the project files for a simple LED board, designed as part of the **[Starting with Altium Designer](https://www.udemy.com/course/starting-with-altium-designer/)** course on Udemy by Robert Feranec.

This project serves as a comprehensive, hands-on introduction to the complete PCB design workflow. The main goal was to practice all the essential Altium Designer features required to create a professional board, from concept to manufacturing.

---

## Key Skills & Project Workflow

As part of this course, this "simple" board project was used to learn and demonstrate the entire hardware design process:

* **Schematic Design:**
    * Drawing the schematic.
    * Annotating components and managing project variants.
    * Updating the schematic from library files.

* **Library Creation:**
    * Creating custom schematic symbols (`.SchLib`).
    * Building custom PCB footprints (`.PcbLib`) based on datasheet specifications.

* **PCB Layout:**
    * Transferring the schematic design to a PCB (`.PcbDoc`).
    * Placing components and defining the board shape.
    * Routing the PCB traces.
    * Creating a 3D model of the final board.

* **Manufacturing Documentation:**
    * Creating a **Bill of Materials (BOM)**.
    * Generating **Assembly Drawings** showing component positions.
    * Generating all necessary manufacturing files:
        * Gerber files
        * Pick and Place file
        * Drill file (NC Drill)

## Repository Contents

* **`*.PrjPcb`**: The main Altium Designer project file.
* **`*.SchDoc`**: The schematic file.
* **`*.PcbDoc`**: The PCB layout file.
* **`*.SchLib`**: The schematic library containing all custom symbols for this project.
* **`*.PcbLib`**: The PCB library containing all custom footprints for this project.
* **`.gitignore`**: The .gitignore file configured for Altium projects to exclude temporary and history files.
