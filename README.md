# If you find this repo and can read this, I haven't finished this yet 
# CR10S5 Dual Extrusion Update With BTT SKR1.4 TURBO 32bit TMC 2208

**This repository is for a very specific setup. Modify it for similar platforms and boards (S4, S3, CR10S, SKR1.3, etc**
The software was compiled with VS Code and the PlatformIO/Auto Build Marlin plugins.

## Specific modifications covered in this repo:
* BigTreeTech SKR 1.4 Turbo 32bit board (LPC1769)
 * TMC2208 in UART mode
* Creality CR10S5
* Dual Extrusion
 * [Thingiverse: CR-10 Dual v6 Extruder Update 1.3](https://www.thingiverse.com/thing:2777673)
* PT100 thermocouple with 5V amplifier board
* Marlin 2.0.6.1
 * This is the release this repo supports, it will not work with older/newer versions without significant changes.

## Hardware
### Things you must buy or have:
* PT100 with 5V amplifier board (I am using the 5V board because that is what I have setup this firmware to manage, I'm sure people smarter than I am will do something else)
* BTT SKR1.4 Turbo (as far as I can tell, the 1.4 turbo/normie is interchangeable, just change the board callouts in the header files)
* extra Nema 17 for extruder 1
* M3/M4 hardware (40mm length bolts is the max size I used)
* Wire for soldering because I chose sensors that don't have JST connectors, do better than I did please
* Soldering iron/solder/flux
* JST connectors and crimpers if you want, I didn't use them and I'm still here
* etc

### Things you must print (or buy):
* Dual extrusion printer head, I used this radical one: [LINKname](link)
* Enclosure for your mainboard, I printed this lovely one: [LINKname](link)
* Nema 17 bracket
* GLCD (graphical lcd) mounting case, I printed this amazing one: [LINKname](link)

## Software
### If you have my exact same setup, you can find the firmware.bin file in the releases page and be on your merry way

### For everyone else, the "SKR1.4 Turbo TMC 2208" is your folder.
Here you can modify the configuration.h, configuration_adv.h, thermistor_42.h, and anything else you need to edit to your printer running. 

## Software Setup Instructions

1. Clone the repo or download the SKR1.4 Turbo TMC 2208 folder
2. Load the folder into VS Code with PlatformIO
3. Open configuration, configuration_adv, thermistor_42, pins_BTT_SKR_V1_4 (lpc1768>pins_BTT_SKR_V1_4) header files

### Changes in configuration.h
`sdfsdfsdf`
