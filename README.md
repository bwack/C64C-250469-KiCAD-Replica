# The C64C 250469 KiCAD replica

A replica of the Commodore 64 250469 motherboard, and schematics.

# BOM


# Interactive BOM

# Schematics

[C64-250469-KiCad.pdf](C64-250469-KiCad.pdf)

# Change log

# YouTube

Check out the videos for this project, and my previous c64 motherboard projects. They are in these playlists:

* [C64C](https://www.youtube.com/playlist?list=PLtQOf_JULmrRxewUc_WUPFes85R2VS0OV)
* [250407](https://www.youtube.com/playlist?list=PLtQOf_JULmrTjnf6mLVKhRkkNlOATiyTX)
* [KU](https://www.youtube.com/playlist?list=PLtQOf_JULmrTGLZCElGG_T1a01JSDP0CP)

# Discrepancies
- Inputs of 4066 in U18 and U21 are named differently.
- Global label INTRES near U6, a INTRES net is crossing, but there is no junction.
- C8 in the schematics is the same as C2 in the layout
- 9VAC global label seems to point the wrong direction
- R16 is anonymous in the schematic
- Power Switch symbols have no reference number and no pin numbers.
- kicad labels will not have slash inside ~{}, but will have them in symbol pin names
- C59 is missing its reference in the schematics. Schematics says it is C19.
- CASS_RD RP3 pin 8 is actually RP5 pin 8.
- C70 at U2 is actually C30.
- C18 in schematic is actually C48 on the pcb.
- RP4 pin 9 in the schematics was not marked with a number.
- C45 in the schematic is C65 in the layout
- Crystal Y1 in the schematics doesn't show the shield grounding and its connection.
- EXT_RESET at the serial port is called EXTRES at U22.
- Diode arrays DA1-4 in the layout was not in the schematics.

Other:
- PB0..7 and PA2 in the schematic share the same net names between to the CIA ICs.

# License and Disclaimer

Copyright Bwack 2023

This documentation describes Open Hardware and is licensed under the CERN OHL v. 1.2.

You may redistribute and modify this documentation under the terms of theCERN OHL v.1.2. (http://ohwr.org/cernohl). This documentation is distributed WITHOUT ANY EXPRESS OR IMPLIED WARRANTY, INCLUDING OF MERCHANTABILITY, SATISFACTORY QUALITY AND FITNESS FOR APARTICULAR PURPOSE. Please see the CERN OHL v.1.2 for applicable conditions.
