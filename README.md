# SF5-Dinput-Modified
StreetFighterV PC DirectInput + Left &amp; Right analog + Select button training mode restart/taunt

This is a drop in DLL replacement for *xinput1_3.dll* that provides DirectInput support for Street Fighter 5 PC. It focuses on having direct bindings for PS3/PS4 controllers that match up with default bindings that would be used on the PS4 version of the game. It also provides features for swapping which slots can be assigned to each controller.

## How to Use?

Drop all included files into **_YourInstallDirectory\steamapps\common\StreetFighterV\StreetFighterV\Binaries\Win64\_** and launch the game. To uninstall, just remove the DLL files from this folder. Yes, that's 2 folders with the same name.

## Features

1. Supports DirectInput as well as XInput devices
2. By holding the Home Button and left or right on the DPad or Left Analog Stick, you can switch between being player 1 or player 2 on any controller (on XInput controller Start+Back can be used if it's not working).
3. You can plug or unplug your devices while the game is running
4. Devices are automatically assigned (first plugged, first player assigned, places are kept).
5. **Modified SELECT button to work as quick restart in training mode and/or taunt in versus mode**
6. **Added preliminary support for Left and Right Analog Joysticks (+ slight deadzones)**
7. **Added experimental right analog scaling movement (PS3 TE stick verified / untested with PS4 controller)**
 
[Enable "Restart Battle" option in SFV to use SELECT button for quick restart](http://i.imgur.com/B1LJUdA)
![Enable "Restart Battle" option in SFV](http://i.imgur.com/B1LJUdA.png)

## Known Bugs

~~Doesn't work with controllers that use the Analog Joystick, only controllers that use the DPad/Hatswitch~~

**(Left and Right Analog Joysticks should now function - tested with PS3 Madcatz TE)**

1. Controllers that aren't PS3/PS4 controllers don't have a way to get proper mapping :(

## Tested with...

1. Hori FC4
2. Sony DualShock 4
3. Hori PS4 VLX
4. PS360+ in any mode
5. **PS3 Madcatz TE (Original TE1)**

## Credits

* @dantarion
* @WydD
* -meign
