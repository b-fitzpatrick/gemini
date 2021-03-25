# geMini
A "genetically engineered" (ge) printer from mostly Prusa (Mini) components

Many components are from the Prusa Mini (https://github.com/prusa3d/Original-Prusa-MINI), including the control board (https://github.com/prusa3d/Prusa-Firmware-Buddy). Many plastic parts are original, though many were inspired by or used some geometry from the Prusa design.

The extruder is the MK3S+ R6 design (https://github.com/prusa3d/Original-Prusa-i3). The belt-retention geometry of the x-carriage was mirrored to account for the motor being on the right side of the machine.

Firmware changes are required to handle the different extruder steps, relocated bed-leveling probe, shorter filament path, and reversed operation of the filament sensor. The "gemini" branch of https://github.com/b-fitzpatrick/Prusa-Firmware-Buddy is based on the official 4.3.1 firmware. (Diff: https://github.com/prusa3d/Prusa-Firmware-Buddy/compare/RELEASE-4.3.1...b-fitzpatrick:gemini)

The Fusion 360 model started out nice, with parameters that could be changed to move the machine through its range of motion. Towards the end, it got a bit sloppy, as I just wanted to print and try the thing. I need to do some assembly clean-up to get it working well again.

I have a second Mini that I plan to convert. When I do this, I'll compile a BOM and document the assembly. In the meantime, in addition to the model, you can see more details in this video: https://youtu.be/Jrde_Tbfxjs

Known issues:
1. I didn't model the bed-alignment posts, and I discovered today, the day I first shared the design, that the bed-leveling probe will hit those posts at y > 175 mm. Need a solution.
2. I'm sure there are others.
