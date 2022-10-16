# XO-Core-XY-Printer
Compact Enclosed Core XY 3D printer with design elements from multiple open-source printers
This printer is based on the Voron V.0 and Tiny M printers.  Basically a larger version of a Voron V.0 with a 220x220x200 build volume.
Uses BTT Octopus for MCU, Raspberry Pi for Klipper.

Use Voron Trident documentation for software setup, then use my config and klicky files.

![](Images/Front%20View.JPG)

# NOTES

1.  I'm still working on a composite BOM for the major components (like frame parts).  I did not render every fastener, screw, bolt, etc.  I learned fusion360 as a hobby, and just didn't have the time and skill for a professional rendor like that (sorry!)
2.  That said - you will need a few packs of M5 bolts (I used button head M5's), and also some M3 (socket head) bolts.  Also get the corresponding M5 and M3 drop-in T-nuts.  I don't have the exact count on these since I had multiple packs in my stash that I picked from.  Typical M5 variety packs should work, but you may need to get a pack of Just longer M5's, from 20mm-40mm for the few longer pieces you will need.  you'll also need a few 3mm square nuts for the x carriage mount.
3.  I'm using 20x40mm corner gussets from Framingtech.com https://www.framingtech.com/20-x-40-gusset at the inside corners of the frame. These are pretty pricey, but they are very well made.  You can substitute these with some regular corner brackets if you want to save some money.
4.  for motors - X and Y can use any typical Nema 17.  I used 48mm Motors.  For the Z motors, you will need to use the pre-geared Nema 17s, like these: https://www.amazon.com/gp/product/B00WATUFIG/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1   These steppers have a built in 5.18:1 gear ratio.  The config file will have the correct rotation distance in the Z_stepper section for these to work.  The Toolhead uses a 36mm round Nema 14 that is typical to other small extruders, like the orbiter or mini-sherpa.
5.  he tool head is a modified V.0 tool head.  it has longer fan ducts for a rapido hotend, and it's 3mm thicker on the front side to account for a 30x30x10mm fan in lieu of a 30x30x7mm fan that is the standard for the V.0.  You can use the stock V.0 in it's place, or any one of the other iterations and mods for this toolhead.
6.  The X carriage is a little different than the standard voron carriage, as it has accomodations for the clicky probe mount, and also a custom backplate behind the nema motor for wire management.  These extra parts can be easily modified to account for different hotends and wiring setups.  right now most of the parts have captured nuts, but I will be working on a version with heatset inserts for a future update.  Some of the captured nuts I'm using at the sides of the mount are 3mm square nuts.  again, this may be updated to heat inserts sometime in the future, when I get around to buying some more.
7.  This IS a work in progress for the most part.  If you find any issues, or have questions, please let me know, and I'll do my best to update the files.
