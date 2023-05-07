# crucible-klipper-backup

This printer is a variation of the printer for ants - Crucible by Maverick

- [https://github.com/PrintersForAnts/Crucible](https://github.com/PrintersForAnts/Crucible)
- [https://github.com/richardjm/Crucible/tree/richardjm/variation](https://github.com/richardjm/Crucible/tree/richardjm/variation)

## Some build documentation

As I went along I created some documentation which can be found here.

[https://richardjm.github.io/crucible](https://richardjm.github.io/crucible)

- STL exports
- A partial BOM of nuts/bolts
- A number of variations that I've incorporated
  - Mini stealthburner (currently running Stealthbrick)
  - Modified colour scheme
  - [Sensorless homing](https://docs.vorondesign.com/community/howto/clee/sensorless_xy_homing.html)
  - Some tools for drilling and alignment
  - Variants for depth of panel clips
  - Reworked base plate
  - [Canbus mounts](https://github.com/KayosMaker/CANboard_Mounts)
  - [Boop](https://github.com/PrintersForAnts/Boop)
  - [Stealth Skirts](https://github.com/VoronDesign/VoronUsers/tree/master/printer_mods/Maverick/V0.2_Stealth_Skirts)
- A number of 'usermods' I've already made
  - Excessive bracing, just because
  - UnklickyNG (now switched to Boop)
  - Slimmer carriage for 17mm pancake motor
  - Beefier idler (left) (now using mod idle_idea)
  - Front bed cover
  - Reduction in branding
  - Shorter rear z-motor mount for increased space in electronics bay
  - Extrusionless x-axis - solo mgn9h

## Hardware and software

The board I've elected to use is a [Fly Puppet 5](https://www.aliexpress.com/item/1005004491731502.html) - which once I get hold of a CM4 should have a nice small footprint.

Using a [Mellow Fly sht36 v2](https://www.aliexpress.com/item/1005004687165673.html) canbus toolhead board with a fly utoc.

Thanks again to [Maz for his Canbus guide](https://maz0r.github.io/klipper_canbus/).

Sensorless homing guide and macros on [Voron design documentation by clee](https://docs.vorondesign.com/community/howto/clee/sensorless_xy_homing.html)
