# Flashing Windows Bootloader
🔙 Back to [Windows Installation](https://github.com/ProjectValhalla/OdinWindowsGuides/blob/main/pages/WindowsInstallation.md)

Make sure you are in Fastboot mode.

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
