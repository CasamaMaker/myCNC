# myCNC
A low cost diy mill cnc. The original idea was create a mill cnc to create my own pcb's (naive of me). 

~~picture~~

## ~~Initial~~ specifications
1. Easy to mount
2. Mostly 3D printed parts (better as fewer different parts be) (5 differents 3D pinter parts)
3. Standard and cheap material to buy (it's why I don't use an aluminum profiles)
4. Dremel as mill machine
5. Basic electronics easy to buy and cheap one's
6. Standard stepper motors, NEMA 17
7. Total price lower than 100€ (wish)(excluding the Dremel machine)
8. ~~Presition for mill PCBs~~
9. Milling material: wood, ~~cooper, aluminium~~
10. Open source code (as Marlin)
11. Work surface ~~> 10x10x2cm~~ 17.5x13.5x2cm


## Inspiration projects
- [MPCNC](https://docs.v1engineering.com/mpcnc/intro/)
- [Low Rider v2](https://docs.v1engineering.com/lowrider/lrv2/indexv2/)


## Shopping list  (107€)
Qty|Concept|Estimated price
---|---|---
1|Arduino Mega|5€
1|[Ramp1.4](https://docs.v1engineering.com/electronics/ramps/)+LCD|20€
5|Stepper motors NEMA17|35€
2.5-3m|Calibrated rods 8mm|9€
50cm|threaded rod|3€
-|Bearings, gears and some screws|8€
-|Gear belt|2€
1|Coil of PLA (or what you want)|25€
~~1~~|~~Dremel~~|~~50€~~

## Some CNC & Milling basics
- [3D printer basics (are also a cnc machines)](https://all3dp.com/2/3d-printer-axis-the-basics-simply-explained/)
- [Homing](https://all3dp.com/2/g28-g-code-homing/)
- [Milling basics](https://docs.v1engineering.com/tools/milling-basics/)

## Marlin configuration
Must change the following points:
- ...

[some examples](https://docs.v1engineering.com/electronics/marlin-firmware/)

## Weaknesses
- Low rigidity (specially in Y axis)
- Backlash as old 3d printer
- Low movements (as expected)
- Poor rpm control (as expected)
- Dificulties to calibrate well the Z axis in all plane
- The work surface must be higher that machine suport, and there's not easy way to subject objecto to mill without use screws
