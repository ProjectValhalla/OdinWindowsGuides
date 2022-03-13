# Flashing Windows Firmware
🔙 Back to [Windows Installation](https://github.com/ProjectValhalla/OdinWindowsGuides/blob/main/pages/WindowsInstallation.md)

Extract odin_windows_firmware.7z to your computer.

Boot Odin to EDL mode (Qualcomm HS-USB QDLoader 9008).

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