# Bambu-Labs-A1-To-Klipper-Conversion (In Development):

The aim of this project is to add klipper functional to the powerful bambu labs a1.
Due to the recent push for "privacy and security", people are wanting to add freedom back to their machines.

To be updated once all the cables and 3d files are availiable.


# Doing any Modifications here WILL void your warrenty of your bambu labs printer.

# Information about what we need:
All items here are from stock a1, attempting to use stock so its an easy upgrade.


# Functions that work:
✔️ Hotend Thermister and all Motors
✔️ PC and EX Fans
✔️
❓ Heated bed (pinout unknown atm)
# Functions that don't work:
❓Filament Sensor : Ribbon cable (unidentified)
- Replace with any filament sensor.
❓Camera Unit : (unidentified 5 pin JST connector) (pinout unknown)
- ? Wire in to the motor board or rpi board
❓Display : (Unidentified Ribbon cable)
- ? Bambu Says A1m uses 4SPI.
❔ AMS lite : Closed Source
- Will develop open AMS lite or find one that can work with klipper (Next Project)

# PCBing:
After the printer works, i will create a pcb so you dont have to splice cables.

Here are some pcbs that I have designed (I HAVE NOT TESTED)

# AMS Board (Designed for Pico MMU)
I may create my own AMS Lite for this printer.
![A1K AMS Board](Images\OpenA1K_AMSBoard.png)