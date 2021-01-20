## Creality Ender 5 Plus w/Stock Touchscreen firmware: BTT SKR 1.4/Mini E3 v2/Stock/Silent Board
 With Configurations and Source Borrowed from [TinyMachines/InsanityAutomation](https://github.com/InsanityAutomation).

## UPDATE 2021/01/19: Updated w/Current Bugfix - Patched Creality_DWIN.cpp, E3 Turbo (UNTESTED!)
## UPDATE 2020/12/06: Created Bugfix Branch
## UPDATE 2020/10/15: Marlin v2.0.7.2 merged
## UPDATE 2020/10/10: Marlin v2.0.7.1 merged
## UPDATE 2020/09/10: Precompiled firmwares

Bin/hex files for all variants listed below are now available in the  **Precompiled** folder

 A selection of custom builds for the Ender 5 Plus:
 
```
; BTT SKR1.4 configurations below assume TMC2209 v1.2 stepper drivers
; Dodge's Special Sauce Custom Build
  DDB_E5P_CUSTOM
; Bilinear bed leveling with Direct Drive, Dual Z steppers (Z0=Z, Z1=E1), and BTT SKR1.4 board
  E5P_BIL_DD_DZ_SKR14
; Unified bed leveling with Direct Drive, Dual Z steppers (Z0=Z, Z1=E1), and BTT SKR1.4 board
  E5P_UBL_DD_DZ_SKR14
; Unified bed leveling with Direct Drive, Dual Z steppers (Z0=Z, Z1=E1), All-Metal Hotend and BTT SKR1.4 board
  E5P_UBL_DD_DZ_AM_SKR14
; Unified bed leveling with Micro Swiss Direct Drive, Dual Z steppers (Z0=Z, Z1=E1), All-Metal Hotend and BTT SKR1.4 board
  E5P_UBL_MS_DZ_SKR14
; Bilinear bed leveling with Direct Drive and BTT SKR1.4 board
  E5P_BIL_DD_SKR14
; Unified bed leveling with Direct Drive and BTT SKR1.4 board
  E5P_UBL_DD_SKR14
; Bilinear bed leveling w/bowden configuration and BTT SKR1.4 board
  E5P_BIL_SKR14
; Unified bed leveling w/bowden configuration and BTT SKR1.4 board
  E5P_UBL_SKR14
; Unified bed leveling with Micro Swiss Direct Drive, Dual Z steppers (Z0=Z, Z1=E1), All-Metal Hotend, BTT TFT35 v3.0  and BTT SKR1.4 board
  E5P_UBL_MS_DZ_GR_SKR14
; Unified bed leveling with Micro Swiss Direct Drive, Dual Z steppers (Z0=Z, Z1=E1), All-Metal Hotend, BTT TFT35 v3.0  and BTT SKR1.4 board
  E5P_UBL_MS_DZ_GR_70_SKR14
; Unified bed leveling with Micro Swiss Direct Drive, All-Metal Hotend, BTT TFT35 v3.0 and BTT SKR1.4 board
  E5P_UBL_MS_GR_SKR14
; Bilinear bed leveling with Direct Drive, Dual Z steppers (Z0=Z, Z1=E1), TFT35 and BTT SKR1.4 board
  E5P_BIL_DD_DZ_GR_SKR14
; Unified bed leveling with Direct Drive, Dual Z steppers (Z0=Z, Z1=E1), TFT35 and BTT SKR1.4 board
  E5P_UBL_DD_DZ_GR_SKR14
; Bilinear bed leveling with Direct Drive, TFT35 and BTT SKR1.4 board
  E5P_BIL_DD_GR_SKR14
; Bilinear bed leveling with Direct Drive, All Metal Hotend, TFT35 and BTT SKR1.4 board
  E5P_BIL_DD_AM_GR_SKR14
; Unified bed leveling with Direct Drive, TFT35 and BTT SKR1.4 board
  E5P_UBL_DD_GR_SKR14
; Bilinear bed leveling w/Bowden config, TFT35 and BTT SKR1.4 board
  E5P_BIL_GR_SKR14
; Unified bed leveling w/Bowden config, TFT35 and BTT SKR1.4 board
  E5P_UBL_GR_SKR14
; Bilinear bed leveling with Direct Drive, Dual Z steppers (Z0=Z, Z1=E1), and BTT SKR E3 Turbo board
  E5P_BIL_DD_DZ_SKRE3Turbo
; Unified bed leveling with Direct Drive, Dual Z steppers (Z0=Z, Z1=E1), and BTT SKR E3 Turbo board
  E5P_UBL_DD_DZ_SKRE3Turbo
; Unified bed leveling with Direct Drive, Dual Z steppers (Z0=Z, Z1=E1), All-Metal Hotend and BTT SKR E3 Turbo board
  E5P_UBL_DD_DZ_AM_SKRE3Turbo
; Unified bed leveling with Micro Swiss Direct Drive, Dual Z steppers (Z0=Z, Z1=E1), All-Metal Hotend and BTT SKR E3 Turbo board
  E5P_UBL_MS_DZ_SKRE3Turbo
; Bilinear bed leveling with Direct Drive and BTT SKR E3 Turbo board
  E5P_BIL_DD_SKRE3Turbo
; Unified bed leveling with Direct Drive and BTT SKR E3 Turbo board
  E5P_UBL_DD_SKRE3Turbo
; Bilinear bed leveling w/bowden configuration and BTT SKR E3 Turbo board
  E5P_BIL_SKRE3Turbo
; Unified bed leveling w/bowden configuration and BTT SKR E3 Turbo board
  E5P_UBL_SKRE3Turbo
; Unified bed leveling with Micro Swiss Direct Drive, Dual Z steppers (Z0=Z, Z1=E1), All-Metal Hotend, BTT TFT35 v3.0 and BTT SKR E3 Turbo board
  E5P_UBL_MS_DZ_TF_SKRE3Turbo
; Unified bed leveling with Micro Swiss Direct Drive, All-Metal Hotend, BTT TFT35 v3.0 and BTT SKR E3 Turbo board
  E5P_UBL_MS_TF_SKRE3Turbo
; Bilinear bed leveling with Direct Drive, Dual Z steppers (Z0=Z, Z1=E1), TFT35 and BTT SKR E3 Turbo board
  E5P_BIL_DD_DZ_TF_SKRE3Turbo
; Unified bed leveling with Direct Drive, Dual Z steppers (Z0=Z, Z1=E1), TFT35 and BTT SKR E3 Turbo board
  E5P_UBL_DD_DZ_TF_SKRE3Turbo
; Bilinear bed leveling with Direct Drive, TFT35 and BTT SKR E3 Turbo board
  E5P_BIL_DD_TF_SKRE3Turbo
; Bilinear bed leveling with Direct Drive, All Metal Hotend, TFT35 and BTT SKR E3 Turbo board
  E5P_BIL_DD_AM_TF_SKRE3Turbo
; Unified bed leveling with Direct Drive, TFT35 and BTT SKR E3 Turbo board
  E5P_UBL_DD_TF_SKRE3Turbo
; Bilinear bed leveling w/Bowden config, TFT35 and BTT SKR E3 Turbo board
  E5P_BIL_TF_SKRE3Turbo
; Unified bed leveling w/Bowden config, TFT35 and BTT SKR E3 Turbo board
  E5P_UBL_TF_SKRE3Turbo
; BTT SKR Mini E3 v2 configurations
; Bilinear bed leveling, BTT SKR Mini E3 2.0 board (SAFEST TO USE - Not all Mini E3 2.0 boards have 512K)
  E5P_BIL_256K_SKRMINIE3_20
; Bilinear bed leveling, BTT SKR Mini E3 2.0 board (USE ONLY IF YOU'RE SURE YOU HAVE 512K)
  E5P_BIL_512K_SKRMINIE3_20
; Unified bed leveling, BTT SKR Mini E3 2.0 board (SAFEST TO USE - Not all Mini E3 2.0 boards have 512K)
  E5P_UBL_256K_SKRMINIE3_20
; Unified bed leveling, BTT SKR Mini E3 2.0 board (USE ONLY IF YOU'RE SURE YOU HAVE 512K)
  E5P_UBL_512K_SKRMINIE3_20
; Unified bed leveling, direct drive, Creality Silent Board
  E5PUBLDDSlnt
; Bilinear bed leveling, direct drive, Creality Silent Board
  E5PBILDDSlnt
; Unified bed leveling, Creality Silent Board
  E5PUBLDZSlnt
; Unified bed leveling, Dual Z, Creality Silent Board
  E5PUBLSlnt
; Bilinear bed leveling, Creality Silent Board
  E5PBILSlnt
; Unified bed leveling, Direct Drive, Creality Stock Board
  E5PUBLDDStck
; Bilinear bed leveling, Direct Drive, Creality Stock Board
  E5PBILDDStck
; Unified bed leveling, Creality Stock Board
  E5PUBLStck
; Bilinear bed leveling, Creality Stock Board
  E5PBILStck
; Unified bed leveling, Dual Z, Direct Drive, All Metal Hotend, Creality Silent Board
  E5PUBLDDDZAMSlnt
```
Name abbreviations were required for the Creality boards due to limitations in their toolsets handling of long filenames in Windows. That's why they look different from the SKR entries.

Key to Filename Feature Indicators:

* BIL - Bilinear Bed Leveling
* UBL - Unified Bed Leveling
* DD  - Direct Drive (short path from extruder to hotend)
* DZ  - Dual Z Steppers; One Z stepper motor cable in Z1 or Z2, the other in E1
* GR  - Graphical Display (TFT35)
* SKR14 - BigTreeTech SKR 1.4 Main Board
* SKRMINIE3_20 - BigTreeTech SKR Mini E3  v2.0
* Slnt - Creality Silent Board
* Stck - Creality Stock Board

## Touchscreen Hardware Configuration - SKR 1.4/Mini E3 2.0 Main Board
Pinouts for the connection of the Creality touchscreen to the BTT SKR boards can be found here: https://imgur.com/rGRCmfs. Please note that the Mini E3 pinouts on the TFT socket are the same as the SKR 1.4.

## Touchscreen Hardware Configuration - Stock/Silent Main Board
If you're using a Creality board, no wiring modifications are needed.

## Touchscreen Software - All Main Boards
The screen flash files have been extracted from the original Insanity Automation distribution and are in the file list above as [DWIN_SET.7z](https://github.com/DodgeDeBoulet/Marlin/raw/E5Plus2.0.7.2/DWIN_SET.7z). You'll need [7-Zip](https://www.7-zip.org/download.html) to decompress them. Copy the extracted DWIN_SET directory to a 4k-sector FAT32 formatted micro SD card, insert it into **the display's** card slot (you'll have to open the PSU case to get to it), and power on the printer. You'll see a lot of text and images flash on the display; it will tell you when it's complete in the upper left corner of the screen. Remove the SD card once it completes.

## BLTouch Support
For the BTT SKR board configuations: These builds assume that you are using the SERVO and PROBE ports for the BLTouch and **not** the Z endstop port. Also, please make sure that you follow the wires back to the BLTouch itself to verify correct wiring. There's a diagram in the respective board's documentation. **IMPORTANT:** The pins for the PROBE port are the reverse of what Creality uses. If you simply plug the 2 wire connector into the PROBE port, it **will not work**. You will neeed to either swap the pins in the plastic shell at the end of the wires, or cut off the plastic tab that aligns the plug in the socket and rotate the plug 180 degrees to insert it "backwards."

* [SKR Mini E3 v2 Instruction Manual](https://github.com/bigtreetech/BIGTREETECH-SKR-mini-E3/blob/master/hardware/BTT%20SKR%20MINI%20E3%20V2.0/Hardware/BTT%20SKR%20MINI%20E3%20V2.0%20Instruction%20Manual.pdf)
* [SKR 1.4/Turbo Instruction Manual](https://github.com/bigtreetech/BIGTREETECH-SKR-V1.3/blob/master/BTT%20SKR%20V1.4/Hardware/BTT%20SKR%20V1.4%20Instruction%20Manual.pdf)

## Original Marlin 2.0.6 README.md
![GitHub](https://img.shields.io/github/license/marlinfirmware/marlin.svg)
![GitHub contributors](https://img.shields.io/github/contributors/marlinfirmware/marlin.svg)
![GitHub Release Date](https://img.shields.io/github/release-date/marlinfirmware/marlin.svg)
[![Build Status](https://github.com/MarlinFirmware/Marlin/workflows/CI/badge.svg?branch=bugfix-2.0.x)](https://github.com/MarlinFirmware/Marlin/actions)

<img align="right" width=175 src="buildroot/share/pixmaps/logo/marlin-250.png" />

Additional documentation can be found at the [Marlin Home Page](https://marlinfw.org/).
Please test this firmware and let us know if it misbehaves in any way. Volunteers are standing by!

## Marlin 2.0

Marlin 2.0 takes this popular RepRap firmware to the next level by adding support for much faster 32-bit and ARM-based boards while improving support for 8-bit AVR boards. Read about Marlin's decision to use a "Hardware Abstraction Layer" below.

Download earlier versions of Marlin on the [Releases page](https://github.com/MarlinFirmware/Marlin/releases).

## Building Marlin 2.0

To build Marlin 2.0 you'll need [Arduino IDE 1.8.8 or newer](https://www.arduino.cc/en/main/software) or [PlatformIO](http://docs.platformio.org/en/latest/ide.html#platformio-ide). Detailed build and install instructions are posted at:

  - [Installing Marlin (Arduino)](http://marlinfw.org/docs/basics/install_arduino.html)
  - [Installing Marlin (VSCode)](http://marlinfw.org/docs/basics/install_platformio_vscode.html).

### Supported Platforms

  Platform|MCU|Example Boards
  --------|---|-------
  [Arduino AVR](https://www.arduino.cc/)|ATmega|RAMPS, Melzi, RAMBo
  [Teensy++ 2.0](http://www.microchip.com/wwwproducts/en/AT90USB1286)|AT90USB1286|Printrboard
  [Arduino Due](https://www.arduino.cc/en/Guide/ArduinoDue)|SAM3X8E|RAMPS-FD, RADDS, RAMPS4DUE
  [LPC1768](http://www.nxp.com/products/microcontrollers-and-processors/arm-based-processors-and-mcus/lpc-cortex-m-mcus/lpc1700-cortex-m3/512kb-flash-64kb-sram-ethernet-usb-lqfp100-package:LPC1768FBD100)|ARM® Cortex-M3|MKS SBASE, Re-ARM, Selena Compact
  [LPC1769](https://www.nxp.com/products/processors-and-microcontrollers/arm-microcontrollers/general-purpose-mcus/lpc1700-cortex-m3/512kb-flash-64kb-sram-ethernet-usb-lqfp100-package:LPC1769FBD100)|ARM® Cortex-M3|Smoothieboard, Azteeg X5 mini, TH3D EZBoard
  [STM32F103](https://www.st.com/en/microcontrollers-microprocessors/stm32f103.html)|ARM® Cortex-M3|Malyan M200, GTM32 Pro, MKS Robin, BTT SKR Mini
  [STM32F401](https://www.st.com/en/microcontrollers-microprocessors/stm32f401.html)|ARM® Cortex-M4|ARMED, Rumba32, SKR Pro, Lerdge, FYSETC S6
  [STM32F7x6](https://www.st.com/en/microcontrollers-microprocessors/stm32f7x6.html)|ARM® Cortex-M7|The Borg, RemRam V1
  [SAMD51P20A](https://www.adafruit.com/product/4064)|ARM® Cortex-M4|Adafruit Grand Central M4
  [Teensy 3.5](https://www.pjrc.com/store/teensy35.html)|ARM® Cortex-M4|
  [Teensy 3.6](https://www.pjrc.com/store/teensy36.html)|ARM® Cortex-M4|
  [Teensy 4.0](https://www.pjrc.com/store/teensy40.html)|ARM® Cortex-M7|
  [Teensy 4.1](https://www.pjrc.com/store/teensy41.html)|ARM® Cortex-M7|

## Submitting Changes

- Submit **Bug Fixes** as Pull Requests to the ([bugfix-2.0.x](https://github.com/MarlinFirmware/Marlin/tree/bugfix-2.0.x)) branch.
- Follow the [Coding Standards](http://marlinfw.org/docs/development/coding_standards.html) to gain points with the maintainers.
- Please submit your questions and concerns to the [Issue Queue](https://github.com/MarlinFirmware/Marlin/issues).

## Marlin Support

For best results getting help with configuration and troubleshooting, please use the following resources:

- [Marlin Documentation](http://marlinfw.org) - Official Marlin documentation
- [Marlin Discord](https://discord.gg/n5NJ59y) - Discuss issues with Marlin users and developers
- Facebook Group ["Marlin Firmware"](https://www.facebook.com/groups/1049718498464482/)
- RepRap.org [Marlin Forum](http://forums.reprap.org/list.php?415)
- [Tom's 3D Forums](https://forum.toms3d.org/)
- Facebook Group ["Marlin Firmware for 3D Printers"](https://www.facebook.com/groups/3Dtechtalk/)
- [Marlin Configuration](https://www.youtube.com/results?search_query=marlin+configuration) on YouTube

## Credits

The current Marlin dev team consists of:

 - Scott Lahteine [[@thinkyhead](https://github.com/thinkyhead)] - USA &nbsp; [Donate](http://www.thinkyhead.com/donate-to-marlin)
 - Roxanne Neufeld [[@Roxy-3D](https://github.com/Roxy-3D)] - USA
 - Chris Pepper [[@p3p](https://github.com/p3p)] - UK
 - Bob Kuhn [[@Bob-the-Kuhn](https://github.com/Bob-the-Kuhn)] - USA
 - Erik van der Zalm [[@ErikZalm](https://github.com/ErikZalm)] - Netherlands &nbsp; [![Flattr Erik](https://api.flattr.com/button/flattr-badge-large.png)](https://flattr.com/submit/auto?user_id=ErikZalm&url=https://github.com/MarlinFirmware/Marlin&title=Marlin&language=&tags=github&category=software)

## License

Marlin is published under the [GPL license](/LICENSE) because we believe in open development. The GPL comes with both rights and obligations. Whether you use Marlin firmware as the driver for your open or closed-source product, you must keep Marlin open, and you must provide your compatible Marlin source code to end users upon request. The most straightforward way to comply with the Marlin license is to make a fork of Marlin on Github, perform your modifications, and direct users to your modified fork.

While we can't prevent the use of this code in products (3D printers, CNC, etc.) that are closed source or crippled by a patent, we would prefer that you choose another firmware or, better yet, make your own.
