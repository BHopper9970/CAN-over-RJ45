## WARNING: THERE ARE ISSUES WITH THIS PROJECT, PLEASE CHECK BELOW IF YOU PLAN TO MAKE THESE
 
# CAN-over-RJ12
A WIP PCB project for carrying CANbus, power and Digital IO over RJ45 wires, primarily for FRC robotics

This repository includes the Kicad Project files for all PCBs (excluding the regulator – designed in EasyEDA) as well as gerber files (exported for JLC, may work with other manufacturers) and 3D models for all PCBs.

for more info, check our [blog post](https://team4788.com/blog/offseason-25-electrical-can-connectors)

### Issues:
- VRM is UNTESTED, use at your own risk. to bypass the VRM, simply solder a wire to the outer two through holes on the VRM header
<img src="https://github.com/CurtinFRC/CAN-over-RJ45/blob/main/Pictures/RioHubVRMBypass.jpg" width="300">

- the Rio Module 12v out is misslabled, the 12v is gnd and the gnd is 12v (swerve module should be fine)
- the vrm retention hole is misaligned (not a massive deal)
- the swerve modules do not pass through DIO lines (otherwise they should be entirely intercompatible)
