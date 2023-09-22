# Archetype_xendstops

![header](./IMG/header.png)

These are two X endstop mounts for the armchair engineering archetype toolhead system (https://github.com/Armchair-Engineering/Archetype/tree/main). 
Instead of mounting on the location where the washers clamp the underside of the mgn12 block, they mount to the probe block. Its also available as a replacement probe spacer.

# Compatibility
It's compatible with:
- all lengths of klicky
- all lenghts of klickyPCB
- all lengths of euclid.

No beacon unfortunately, except with the spacer. (although no guarantees if that would work either, i have no idea how beacon works)
Its also not compatible with flipped gantries, as it uses the xy joint's bottom part to click the endstop button. So no mjolnir or atrocity :( I'll see if i can think of a top mounted solution soon.

The probe spacer has an integrated support block due to the required printing orientation. The endstop mount should stick out upwards.

The probe mounted version works well for me in my trident. Please create an issue if you figure out incompatibility problems.

# Instructions

Solder your two wire leads at a 90 degree angle so they come out to the front.
Run these wires down, back up through the inside of the hotend mount, and then out again along your thermistor and heater wires to wherever.
The probe mount uses two m3x18 instead of m3x16. M3x20 with some washers works well too (the probe mount is 3mm thick). The spacer mounts however it usually does.

![header](./IMG/wire_routing.png)
