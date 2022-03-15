
🔙 Previous Step: [Formatting and Perparing the Odin](https://github.com/ProjectValhalla/OdinWindowsGuides/blob/main/pages/FlashingProjectValhallaFirmware.md)

# Flashing ProjectValhalla Firmware

Extract `project_valhalla_firmware.7z` to your computer.

## Boot Odin to EDL mode (Qualcomm HS-USB QDLoader 9008).
There are three ways to enter EDL mode:

### 1. Key Combo (Suggested)
With your device powered off, hold the Volume Up Button + Volume Down Button while plugging your device into your pc. The Odin boot screen will flash for a moment then the screen will go black.

### 2. Via ADB
Open windows powershell or command prompt and use the ADB write command:

```adb reboot edl```

### 3. Via fastboot
Select **Emergency Mode**.

## Setup Qfil

Extract the `Qualcomm_Flash_Image_Loader_v2.0.3.5.zip` and run QFIL.exe.

In the bottom right of the program you will see that is says `Storage Type: emmc`, click on this and change it to `ufs`.

## ⚠️ If at any point you get a failure message in the QFIL program, long press the power button on the Odin until the device boots and restart ELD mode.

## Click Select Port button and select correct COM Port for Odin.
![QFIL ComPort](/images/qfil_comport.jpg)

## Open QFIL Application and choose Flat Build for Select Build Type.
![QFIL Start](/images/qfil_download_start.jpg)

## Click Browse button and select **prog_firehose_ddr.elf** in Select Programmer section in the `project_valhalla_firmware` folder.
![QFIL Firehose](/images/qfil_firehose.jpg)

## Click Load XML button select all **rawprogram.xml** and **patch.xml** in the `project_valhalla_firmware` folder.
![QFIL Rawprogram](/images/qfil_rawprogram.jpg)
![QFIL Patch](/images/qfil_patch.jpg)

## Click Download and wait until the download process finishes.
![QFIL Finish](/images/qfil_download_finish.jpg)


### If the Odin does not reboot automatically, hold the power button until it’s rebooted.

## Next Step: [Flashing the Windows Bootloader](https://github.com/ProjectValhalla/OdinWindowsGuides/blob/main/pages/FlashingWindowsBootloader.md)
