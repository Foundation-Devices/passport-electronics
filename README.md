# Passport Electronics

This repository contains the circuit designs for Passport, an open source Bitcoin hardware wallet made by Foundation Devices. While the circuit designs are complete, Foundation Devices is still in the prototyping stage and will likely make changes prior to production.

<img width="1165" alt="main board block diagram" src="https://user-images.githubusercontent.com/14018740/98994794-5fa6eb80-24fe-11eb-8832-4fdf604ca25d.png">

Above is a basic block diagram for Passport's Main Board.

## Project Structure
Passport consists of three circuit boards:
- Main Board
- Camera Board
- Battery Board

**Main Board** contains most of the components, including the processor and secure element.

**Camera Board** contains the camera and attaches to the Main Board.

**Battery Board** contains two variants – North and South – that are populated with different components. Notably, the Battery Board South contains pogo pins that provide power to the Main Board.

### Folder Organization
Each folder contains three subfolders:
- Assembly
- Fabrication
- Source Files

**Assembly** contains data for assembling components onto a bare circuit board. It includes drawings, bill of materials, and coordinates for pick-and-place and test points.

**Fabrication** contains data for the circuit board fabricator. It includes drawings, Gerber files, and coordinates for drilling and test points.

**Source Files** contains circuit board designs. It includes circuit schematics and Altium design files.

Circuit designs can only be opened with Altium. We are exploring exporting these designs in multiple file formats, including formats that can be used with open source PCB design software.

If you are interested in using KiCAD, you may try this Altium to KiCAD converter: https://github.com/thesourcerer8/altium2kicad/.

### Documenting Changes
This repository includes a CHANGES.txt file. We will document all design changes in this file. If you submit a pull request that makes changes to the circuit designs, please update CHANGES.txt with a brief description of your changes.

## Licensing
This project, and every file included in this repository, is licensed under CERN-OHL-S v2 – a viral, copyleft, open source license. CERN-OHL-S v2 is similar in goals to GPLv3, but is specifically designed for hardware projects.

You are welcome to use these designs for any purpose, but you must comply with the terms of the license. This includes licensing derivative work as CERN-OHL-S v2, preserving copyright notices, and more. Instructions are included in LICENSE_GUIDE.txt. Feel free to contact us with any questions about licensing.

Included in this repository in LICENSE.txt is the full text of CERN-OHL-S v2.

### License Notice
You may redistribute and modify this source and make products using it
under the terms of the CERN-OHL-S v2 (https://ohwr.org/cern_ohl_s_v2.txt).

This source is distributed WITHOUT ANY EXPRESS OR IMPLIED WARRANTY,
INCLUDING OF MERCHANTABILITY, SATISFACTORY QUALITY AND FITNESS FOR A
PARTICULAR PURPOSE. Please see the CERN-OHL-S v2 for applicable conditions.

Source location: foundationdevices.com/passport-electronics

As per CERN-OHL-S v2 section 4, should You produce hardware based on this
source, You must where practicable and applicable maintain the Source Location
visible (1) on the packaging of the hardware, (2) on the circuit board(s) via
silkscreen or copper, (3) in any documentation, and (4) on other products you
make using this source.
