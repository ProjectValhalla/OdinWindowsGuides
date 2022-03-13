
🔙 Previous Step: [Formatting and Perparing the Odin](https://github.com/ProjectValhalla/OdinWindowsGuides/blob/main/pages/FlashingProjectValhallaFirmware.md)

# Flashing ProjectValhalla Firmware

Extract `project_valhalla_firmware.7z` to your computer.

## Boot Odin to EDL mode (Qualcomm HS-USB QDLoader 9008).
There are three ways to enter EDL mode:

### 1. Key Combo (Suggested)
Hold the Volume Up Button + Volume Down Button while plugging your device into your pc

### 2. Via ADB
Open windows powershell or command prompt and use the ADB write command:

```adb reboot edl```

### 3. Via fastboot
Select **Emergency Mode**.

## Click Select Port button and select correct COM Port for Odin.
![QFIL ComPort](/images/qfil_comport.jpg)

## Open QFIL Application and choose Flat Build for Select Build Type.
![QFIL Start](/images/qfil_download_start.jpg)

## Click Browse button and select **prog_firehose_ddr.elf** in Select Programmer section.
![QFIL Firehose](/images/qfil_firehose.jpg)

## Click Load XML button select all **rawprogram.xml** and **patch.xml**.
![QFIL Rawprogram](/images/qfil_rawprogram.jpg)
![QFIL Patch](/images/qfil_patch.jpg)

## Click Download and wait until download process finish.
![QFIL Finish](/images/qfil_download_finish.jpg)


If the Odin is not reboot automatically hold Odin power button until it’s rebooted.
