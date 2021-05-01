{% include navigation.md %}

## Bill Of Material (BOM)
**This is a work in progress. Required quantities might not be correct yet. Please verify this yourself before ordering**  
The required materials are split up in 4 parts:
* [3D Prints](#3d-prints)
* [Hardware](#hardware)
* [PCB](#pcb)
* [Tools](#tools)

---
### 3D Prints
The following parts are required to be 3D Printed. For more details, please see the [3D printing section]({{ site.baseurl }}{% link 3dprinting.md %}).
* 1x Body
* 1x Finger guard
* 1x Top
* 1x Flange
* 13x Square pushbuttons
* 6x Round pushbuttons
* 2x Rocker switch base
* 2x Rocker switch cover
* Dobber switch (Base + Stem)

---
### Hardware
* 1x STM32 Blue Pill
* 27x diodes (Get some spares. Type 1N4001 or something similar. Most 1NXXXX will work. Body length: ~4.5 mm)
* 8x 6x6x4.3 mm tactile switches (just get a pack of 50 or 100) (If possible, use 500 gram actuation fore switches instead of the default 160 gram)
* 2x ON-OFF-ON 3 position Toggle switches (About 30x15mm. Like an E-TEN1122)
* 19x Cherry MX (or compatible) switches
* SOME AMOUNTx M3xLENGTH bolts
* \[**Optional**\] 2x 20 pin female 2.54mm headers (if you don't want to solder the Blue Pill directly to the PCB)
* \[**Optional**\] Threaded brass inserts\[\*\]
* \[**Optional**\] 2x 27R resistors and spare USB cable to cut up\[\*\]

\[\*\] The brass inserts are not necessary, but do improve the longevity of the 3D printed base if you need to take it apart and put it together a couple of times.  
**IMPORTANT:** To use the brass inserts, print the BRASS_INSERTS version of the body file.

---
### PCB
For this project you need to order a custom PCB. The design files can be downloaded [here](nolinkyet). You can order this PCB through a supplier like JLCPCB or PCBWay or something similar. You only need 1 base PCB, but most of the time it is just as expensive to order 5 or 10.  

To order the PCB, you need to:
* Create an account on the website
* Upload the file named F16\_ICP\_GERBERS\_\[revision\].zip
* Check if it looks alright in the online preview
* Verify quantity (5 or 10)
* \[**Optional**\] select black PCB

Most order will be manufactured in a couple of days and delivered within 2 - 6 weeks, depending on shipping options and destination.

---
### Tools
Some basic tools are required to assemble the ICP. Depending on the type of finishing, some extra tools are required. Please read through the [finishing]({{ site.baseurl }}{% link finishing.md %}) section to determine which supplies you need.  
**Required tools:**
* STM32 programmer (ST-link V2)
* Soldering iron and solder
* (Flush) wire cutters
* Screwdrivers

**Optional tools:**
* White and/or black spray paint
* Laser cutter/engraver
* Normal inkjet/laserprinter and transparent sheets

### Next step: [3D printing]({{ site.baseurl }}{% link 3dprinting.md %})