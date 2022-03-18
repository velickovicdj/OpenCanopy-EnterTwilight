# OpenCanopy EnterTwilight
OpenCanopy minimal theme for use with OpenCore bootloader.

**NOTE:** Compatible with OpenCore 0.7.0 and higher.

## Installation
Copy icons to EFI/OC/Resources/Image/velickovicdj/EnterTwilight, then in your config.plist:

- Misc -> Boot -> `PickerMode: External`
- Misc -> Boot -> `PickerAttributes: 17` (or whichever [value](https://dortania.github.io/docs/latest/Configuration.html) you prefer)
- Misc -> Boot -> `PickerVariant: velickovicdj/EnterTwilight`

That's it! After a reboot, you'll be greeted with something like this:

![EnterTwilight Preview](/Preview.png)
