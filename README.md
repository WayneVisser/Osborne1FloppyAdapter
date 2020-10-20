Floppy Adapter for the Osborne 1
--------------------------------

1. The Osborne 1 uses a non-standard Shugart floppy interface where +12V and +5V for the drive are
fed through the floppy cable.  This KiCAD project accounts for that and creates a nice tidy 
interface to a GoTek floppy disk emulator.  There is no need to cut traces as is the case when using a 
generic floppy adapter.

2. +5V power for the GoTek is taken from the floppy cable.

3. Jumper only S1 on the GoTek.

4. GoTek part number is: SFR1M44-U100K

5. GoTek connector is a Sullins PPPC172LJBN-RC

6. Program the GoTek with FlashFloppy firmware:  https://github.com/keirf/FlashFloppy

![Adapter Pic1](https://vissernet.ca/picture_library/FloppyAdapter_V1.1.png)

![Adapter Pic2](https://vissernet.ca/picture_library/FloppyAdapter_01.png)

![Adapter Pic3](https://vissernet.ca/picture_library/FloppyAdapter_02.png)

**References**

Electrical Details:

* [vcfed](http://www.vcfed.org/forum/showthread.php?56999-Osborne-1-Gotek-Floppy-Emulator-SUCCESS!)

3D printed 3.5" to 5.25" Floppy Case Adapter:

* [thingverse](https://www.thingiverse.com/thing:2217061)

Richard Loxley has done a lot of good work on the Osborne 1.  His site is a *great* resource for
how to get CP/M-formatted floppy disk images working on the GoTek.

* [Richard Loxley](https://www.richardloxley.com/2018/03/30/retro-challenge-2018-04/)

Just want the board?

* [OSHPark](https://oshpark.com/shared_projects/k4YXJYxn)
