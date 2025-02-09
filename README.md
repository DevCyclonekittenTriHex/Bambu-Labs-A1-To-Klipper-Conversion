# Bambu-Labs-A1-To-Klipper-Conversion (In Development):

The aim of this project is to add klipper functional to the powerful bambu labs a1.
Due to the recent push for "privacy and security", people are wanting to add freedom back to their machines.

Bill of Materials :[BOM](https://docs.google.com/spreadsheets/d/1AV4G6ZVxCB9UINE7sgqaOE8Zk1H3DC7Mk_idkd3VZ8s/edit?usp=sharing)

Discord : [A1 Klipper Mod](https://discord.gg/Ssx37MAkGv)

# Doing any Modifications here WILL void your warrenty of your bambu labs printer.

# Information about what we need:
All items here are from stock a1, attempting to use stock so its an easy upgrade.


# Solved:
✔️ Motors : 4 Pin JST XH connector
- Insert as usual

✔️ Hotend Thermister : Wierd Connector
- Splice into 2 Pin JST GH

✔️ Hotend Heater : Wierd Connector
- Splice into 2 Pin JST XH

✔️ Bed Levelling:
- Add Biqu Microprobe or Bed Levelling Sensor

✔️ Part Cooling Fan: 24v 0.25a
- Connected 4 pin JST XH, might need splicing

✔️ Hotend Cooling Fan: 5v 0.4a
- Connected by 5 pin JST XH, Needs splicing to fit in port. Possibly a voltage converter.

# Unsolved:
❓Filament Sensor : Ribbon cable (unidentified)
- Replace with any filament sensor.

❓Eddy Sensor : Two wires (unidentified)
- ? Possibly plug into rpi and somehow code into klipper flow calibration.

❓Heatbed : (unidentified)
- ? Probs just get bambu ac board and find pinout.

❓Camera Unit : (unidentified 5 pin JST connector) (pinout unknown)
- ? Wire in to the motor board or rpi board

❓Display : (Unidentified Ribbon cable)
- ? Bambu Says A1m uses 4SPI.

❔ AMS lite : Closed Source
- Will develop open AMS lite or find one that can work with klipper (Next Project)




