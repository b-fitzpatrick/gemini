# gemini
A "genetically engineered" (Ge) printer from mostly Prusa (Mini) components

Many components are from the Prusa Mini (https://github.com/prusa3d/Original-Prusa-MINI), including the control board (https://github.com/prusa3d/Prusa-Firmware-Buddy). Many plastic parts are original, though many were inspired by or used some geometry from the Prusa design.

The extruder is the MK3S+ R6 design (https://github.com/prusa3d/Original-Prusa-i3). The belt-retention geometry of the x-carriage was mirrored to account for the motor being on the right side of the machine.

Firmware changes are required to handle the different extruder steps, relocated bed-leveling probe, and reversed operation of the filament sensor. The "gemini" branch of https://github.com/b-fitzpatrick/Prusa-Firmware-Buddy is based on the official 4.3.1 firmware. (Diff: https://github.com/prusa3d/Prusa-Firmware-Buddy/compare/RELEASE-4.3.1...b-fitzpatrick:gemini)
