# UDI RC U816

Recently I organised an activity where participants with no prior experience could fly a drone. After some research the drone chosen was the UDI RC U816.
Some of the reasons why this drone was chosen are; the relatively low price (€22), the sturdiness (metal frame), it comes with dual batteries and a dual charger, it is neither too small nor too big.
The biggest disadvantage is that it comes with a tiny – mostly cosmetic – plastic hood over the central electronics, and no other protection.

## Frame

I looked up frames for this drone online at [Thingiverse](https://thingiverse.com), and [found one](https://www.thingiverse.com/thing:34030), but I did not like the execution of the design. Several parts intersect rather crudely without any polishing. However, I did like the chosen cross-section design. Therefore I decided to design a replacement in FreeCAD, using the same cross-section shape for the frame.

The current iteration of the frame is not great yet, but it worked well enough for the activity. After several hours of being flown into walls, ceilings and furniture, both frames had cracked, but the drone propellers were still intact.

The current version of the frame has a click mechanism to keep the frame in place. However, the frame still comes off rather easily. For the activity I had glued the frame to the metal bars of the U816. Afterwards, I peeled the damaged frames off, so I could refit new ones.

Note: The frame has channels for the motor wires, be careful that the wires are correctly in the channels. I had some wires nearly shear off when trying to click the frame in place with the wires in the wrong position.

### Weight

The frame weighs about 12.5 grammes when printed in PLA. The drone can easily lift that much weight. During preliminary testing I feared that the drone (without frame) would be too hard to control for inexperienced fliers. However when the frame had been added, the drone seemed somewhat easier to control.

## Slicing

I slice using the latest Slic3r Prusa Edition. I suggest using 0.20mm layer height.

### Orientation

The frame comes with a built-in brim, since Slic3r Prusa Edition cannot brim on the inside of objects. The inner brim is required to prevent the frame from being levered off the print bed.

Reduce the required print bed size, turn the frame 45 degrees along the Z-axis.

To correctly orient the frame, flip it upside down along the X- or Y-axis.

### Infill Pattern

To ensure the built-in brim is attached well, and easy to remove, set the _Print Settings_ → _Infill_ → _Fill pattern_ to _Concentric_.

## Printing

Printed with an Original Prusa i3 Mk3 using PLA
