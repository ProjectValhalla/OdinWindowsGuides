# Windows Installation

## Warnings ⚠️
This is **NOT** an official Windows port made by AYN. AYN will **NOT** provide support for this operating system and installing this may in fact VOID your warranty.

This is a community effort project, and thus we cannot guarantee no issues when attempting to install this port on your Odin.

Furthermore, this installation may brick your device. Do so at your own risk! We take no responsibility for hardbricked devices!

## What you’ll need :

You can see detail information about the release here : [Odin Windows Release Page](https://github.com/ProjectValhalla/OdinWindowsRelease)

### Hardware :
- A Windows based computer (vm will work)
- An **Odin-Base** (4GB RAM with 64GB Storage) or an **Odin-Pro** (8GB RAM with 128GB or 256GB Storage)
- An 8GB or larger USB flash drive formatted to FAT32
- A USB-A to USB-C adapter to plug the flash drive into the C port of the Odin

### Prerequisite Software:
- [QFIL Tool](https://qfiltool.com/category/download)
- [Android Studio or Android Command Line Tools](https://developer.android.com/studio#downloads) (ADB and Fastboot tools)
- [project_valhalla_firmware.7z](https://github.com/ProjectValhalla/OdinWindowsRelease/releases/download/alpha.1/project_valhalla_firmware.7z)

### Firmware Images and installer files:
- EDK2 Bootloader :
  - [boot-odin-base.img](https://github.com/ProjectValhalla/OdinWindowsRelease/releases/download/alpha.1/boot-odin-base.img) for **Odin-Base**
  - [boot-odin-pro.img](https://github.com/ProjectValhalla/OdinWindowsRelease/releases/download/alpha.1/boot-odin-pro.img) for **Odin-Pro**
- [odin_windows_installer.7z](https://github.com/ProjectValhalla/OdinWindowsRelease/releases/download/alpha.1/odin_windows_installer.7z)
- `install.wim` or `install.swm` files from a Windows ARM64 release 

##  Steps :
- Step 1: [Flashing ProjectValhalla Firmware](https://github.com/ProjectValhalla/OdinWindowsGuides/blob/main/pages/FlashingProjectValhallaFirmware.md)
- Step 2: [Flashing Windows Bootloader](https://github.com/ProjectValhalla/OdinWindowsGuides/blob/main/pages/FlashingWindowsBootloader.md)
- Step 3: [Installing Windows 11](https://github.com/ProjectValhalla/OdinWindowsGuides/blob/main/pages/InstallingWindows11.md)
