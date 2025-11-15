## Bambu Lab A1 Klipper Conversion (In development)

## Join Chaz's [**Discord Server**](https://discord.gg/W6B5mBejuC) to help with all bambu labs klipper mods.

> [!Caution]
> Doing any modifications may void your warrenty! 
> [!Caution]
> This Project is in currently not finished, this conversion is done fully at your own risk, I am not liable for any damages done to your machine.

This is constantly being updated, the docs for the conversion will be [Here!](https://devcyclonekittentrihex.github.io/A1K-Documentation/Docs/)

# Aim
The aim of this open source project is to create drop in circuit boards for the Bambu Labs A1 and A1 mini machines; and to provide a good framework to promote modding of these machines. This project will try to intergrate every part from the original printer to make the upgrade seamless. This will give back people privacy and a fully lan or offline system to print.

Currently, I have designed the a1 mainboard and a1/a1m toolhead boards, and am currently going through revisioning.
My target for the pcbs are to order them by November 30th

# Functions

Does work:
- Full hotend heating 
- XYZ Movement
- Stock Part Cooling Fans
- Auto Bed Levelling (with biqu microprobe)
- Filament Runout (with biqu sfs2)

Does not work:
- Heated Bed : Currently have the pinout for it, will be implemented in pcbs.
- Filament Sensor : It is a linear hall sensor, pinout unknown. Will attempt to find.
- AMS Lite : Closed source, other open mmus are compatible
- Display : An unidentified display that is possibly using 4SPI

# Previous Experiments
I previously hooked up an skr pico to the printer, and got it printing without a heated bed. Here is the footage. I also killed my mainboard so there is no more footage.
https://youtu.be/fLf-GMceLxE