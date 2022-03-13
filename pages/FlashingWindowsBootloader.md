🔙 Previous Step: [Formatting and Preparing the Odin](https://github.com/ProjectValhalla/OdinWindowsGuides/blob/main/pages/FlashingProjectValhallaFirmware.md)

# Flashing Windows Bootloader

You may need to hold the power button for 10+ seconds for Odin to boot.

Make sure you are in Fastboot mode when it does. Your screen should look like this:
![Odin Valhalla Fastboot](/images/valhalla_fastboot.jpg)


## Open a terminal and navigate to where your `boot-odin-base.img` or `boot-odin-pro.img` is located.

For Odin Base Write command:
```
fastboot flash boot boot-odin-base.img
```

For Odin Pro Write command:
```
fastboot flash boot boot-odin-pro.img
```

## Booting

Make sure START is selected on the odin and hit the power button to confirm it. The Odin will then boot.

You may also use the fatboot reboot command:
```
fastboot reboot
```
##Step 3: [Installing Windows 11](https://github.com/ProjectValhalla/OdinWindowsGuides/blob/main/pages/InstallingWindows11.md)
