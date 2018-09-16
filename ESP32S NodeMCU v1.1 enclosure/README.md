# ESP32S NodeMCU v1.1 enclosures

These enclosures are my first attempt at making 3D printed enclosures.

They have zero tolerance, and will be a tight fit. But in general the 1mm thick material will be flexible enough that builtin tolerance is not needed. If you cannot fit the PCB in the enclosure, consider hand-sanding the rough edges of the PCB down *very* slightly. Just a tenth of a millimetre might be enough.

## Header version

If you have an ESP32S NodeMCU v1.1 board with soldered-on headers, use this one.

## No header version

If you have an ESP32S NodeMCU v1.1 board without any soldered-on headers, use this one. There will be 1mm of space between the PCB and inside of the lid, except along the edges where the lid's inner rim touches the PCB.

## PIR sensor version

I made this one to house a PIR sensor PCB I had. The PIR sensor fits in the lid. It is supposed to be used with an ESP32S NodeMCU v1.1 board without headers. Connect the PIR sensor with a small flatcable, so you can easily take off the lid without damaging anything. You'll have to take off the lid to change the potentiometers.

## Slicing

I slice using the latest Slic3r Prusa Edition. I suggest using 0.20mm or 0.10mm layer height, to ensure that the 1mm thick verticals fit exactly in a whole number of layers. Although, when I accidentally printed my first attempt with 0.15mm layer height, it still fit perfectly.

I used 100% infill, though I'm not sure whether the model actually has any parts that are considered infill.

Note: The AMF exports are not aligned with the base plane. In Slic3r I usually apply a turn around the Y-axis, and this causes the program to suddenly snap them correctly to the ground plane. The enclosure must be turned 180° around either the X- or Y-axis. For the lid I generally apply a 0° turn, to snap it to the ground plane without actually turning it.

## Printing

Printed with an Original Prusa i3 Mk3 using PLA


Note: At the time of writing, only an older version of the one with headers has been printed.

