# Marlin

Originally made for: v2.1.2.1

My Marlin Tuning for Creality Ender 3 Max (original version, not NEO).
Upgraded with Creality Sprite Pro direct-drive all-metal extruder/hotend.
No auto-leveling, which the stock Creality Sprite firmware is built for.

I'm making this available in case it is helpful to others. 
No warranty expressed or implied.
See full Marlin distribution (linked below) for more details.
This is only the "Marlin" folder, you will need the full distribution to build.
https://github.com/MarlinFirmware

The only files actually modified are:

* Configuration.h
* Configuration_adv.h
* _Bootscreen.h
* _Statusscreen.h

Defaults for Ender 3 Max imported from: https://github.com/MarlinFirmware/Configurations

The following changes have been made:

* Manual (assisted) Leveling enabled.
* Max Temp now 300° for ABS.
* Adjusted PLA preheat temps.
* Changed ABS preheat to TPU.
* Adjusted motion settings (mm) for filament change.
* Adjusted runout sensor parameters for new mounting position on top rail.

Just making this available in case it helps others.
Please see the original Marlin documentation at https://marlin.org
