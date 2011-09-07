Freetronics Power Regulator 28V
===============================
Copyright 2011 Freetronics Pty Ltd  
Freetronics site:  <www.freetronics.com>  
Freetronics email: <info@freetronics.com>  

Module to regulate power supplied on Power-over-Ethernet connection
down to 7Vdc for supply to the on-board voltage regulator in an
Arduino Uno, Freetronics Eleven, or other compatible board
using the Freetronics Ethernet Shield, or an EtherTen.

Features:

 * Adds Power-over-Ethernet "PD" (powered device) support to the
   Freetronics Ethernet shield.
 * Input voltage range 9-28Vdc.
 * Output voltage limited to 7V and fed to Arduino on-board voltage
   regulator via Ethernet shield for further regulation down to 5V.
 * Input protection diode to prevent damage due to reverse polarity.
 * Plugs directly onto Freetronics Ethernet Shield and EtherTen.
 * "Power on" LED.
 * Output voltage can be set to 5V for use as a general-purpose
   5V power supply module.


More information is available at:

  http://www.freetronics.com/pr28v

The "docs" folder within this repository includes a handy copy of the
schematic in PDF format and image(s) of the pcb.


INSTALLATION
------------
The design is saved as an EAGLE project. EAGLE PCB design software is
available from www.cadsoftusa.com free for non-commercial use. To use
this project download it and place the directory containing these files
into the "eagle" directory on your computer. Then open EAGLE and
navigate to Projects -> eagle -> PowerRegulator28V.


DISTRIBUTION
------------
The specific terms of distribution of this project are governed by the
license referenced below.


LICENSE
-------
Licensed under the TAPR Open Hardware License (www.tapr.org/OHL).
The "license" folder within this repository also contains a copy of
this license in plain text format.
