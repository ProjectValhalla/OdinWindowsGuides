# Flashing ProjectValhalla Firmware
🔙 Back to [Windows Installation](https://github.com/ProjectValhalla/OdinWindowsGuides/blob/main/pages/WindowsInstallation.md)

Extract `project_valhalla_firmware.7z` to your computer.

## Boot Odin to EDL mode (Qualcomm HS-USB QDLoader 9008).
There are several ways to enter EDL mode:

### Via ADB
Write this command:

```
adb reboot edl
```
### Via fastboot
by selecting **Emergency Mode**.

### or Using hardware buttons
- Turn off yur Odin
- Then, press and hold the **Power Button** + **Volume Up Button**  + **Volume Down Button**. and immediately connect the device to the PC.

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
