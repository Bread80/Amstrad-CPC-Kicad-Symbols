# Kicad

KiCad symbols for Amstrad CPC custom ICs and some related devices.
==================================================================

These ICs were used in the Amstrad CPC464, CPC664, CPC472 and CPC6128.

NOTE: While I have taken every precaution to verify the accuracy of the data contained in this repository these symbols have not been verified against original hardware.

Included symbols
----------------

40007/40008 Gate array. These both have the same the same pinout and function but the latter is a revised design which doesn't need a heatsink.

40010 Gate array. This functions the same as the 40007 but has a different pinout.

40030 PAL/HAL. This is the memory manager used in the Amstrad CPC6128

AY-3-8910 Programmable Sound Generator. This is an alternative to the AY-3-8912 which was used in the CPC range.

How To Use
----------

To add the library to KiCad:

* In either the Project Editor or the Schematic Editor, select Preferences -> Manage Symbol Libraries from the main menu.

* Select either the Global Libraries or the Project Specific Libraries tab depending on preference.

* Click the + (Add empty row to table) button just below the table. This will insert an extra, blank, row to the table.

* In the Nickname field enter a suitable nickname.

* In the Library Path enter the path and filename of the .lib file for the library (or use the file browser).

* Click OK to save and leave the Symbol Libraries dialog.

Resources
---------

Gate array pinouts: https://www.cpcwiki.eu/index.php/Gate_Array_and_ASIC_Pin-Outs

Amstrad CPC schematics: http://www.cpcwiki.eu/index.php/Schematics

"Gate Array Decapped": A forum thread discussing the reverse engineering of a 40010. The link is to the post containing the latest revision (at the time of writing) of the schematic. https://www.cpcwiki.eu/forum/amstrad-cpc-hardware/gate-array-decapped!/msg170713/#msg170713