🔙 Previous Step: [Formatting and Preparing the Odin](https://github.com/ProjectValhalla/OdinWindowsGuides/blob/main/pages/FlashingProjectValhallaFirmware.md)

# Flashing Windows Bootloader

You may need to hold the power button for 10+ seconds for Odin to boot.

Make sure you are in Fastboot mode when it does. Your screen should look like this:
![Odin Valhalla Fastboot](/images/valhalla_fastboot.jpg)

For Odin Base Write command:
```
fastboot flash boot boot-odin-base.img
```

For Odin Pro Write command:
```
fastboot flash boot boot-odin-pro.img
```

Then select Start in Odin unit to start the boot process.

or you can write reboot command:
```
fastboot reboot
```
