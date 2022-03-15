# Windows Installation

## ⚠️ Warning ⚠️
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
- [Qualcomm EDL Drivers](https://github.com/ProjectValhalla/OdinWindowsGuides/blob/main/pages/Qualcomm%20USB%20Driver%20v2.2.0.0%20Setup.zip)
- [QPST Package which contains the QFIL Tool](https://github.com/ProjectValhalla/OdinWindowsGuides/blob/main/pages/QPST.zip)
- [Google USB Driver](https://www.xda-developers.com/install-adb-windows-macos-linux/)
- [Android Studio or Android Command Line Tools](https://www.xda-developers.com/install-adb-windows-macos-linux/)
- [Project Valhalla firmware .7z archive](https://github.com/ProjectValhalla/OdinWindowsRelease/releases/download/alpha.1/project_valhalla_firmware.7z)

### Firmware Images and installer files:
- EDK2 Bootloader :
  - [boot-odin-base.img](https://github.com/ProjectValhalla/OdinWindowsRelease/releases/download/alpha.1/boot-odin-base.img) for **Odin-Base**
  - [boot-odin-pro.img](https://github.com/ProjectValhalla/OdinWindowsRelease/releases/download/alpha.1/boot-odin-pro.img) for **Odin-Pro**
- [odin_windows_installer.7z](https://github.com/ProjectValhalla/OdinWindowsRelease/releases/download/alpha.1/odin_windows_installer.7z)
- [`install.wim`](https://drive.google.com/file/d/1ArFcrWFRzRd-J8sUqo-oFpyy2p_mSS2m/view?usp=sharing) the windows installation file 

##  Steps :
- Step 1: [Formatting and Preparing the Odin](https://github.com/ProjectValhalla/OdinWindowsGuides/blob/main/pages/FlashingProjectValhallaFirmware.md)
- Step 2: [Flashing Windows Bootloader](https://github.com/ProjectValhalla/OdinWindowsGuides/blob/main/pages/FlashingWindowsBootloader.md)
- Step 3: [Installing Windows 11](https://github.com/ProjectValhalla/OdinWindowsGuides/blob/main/pages/InstallingWindows.md)
