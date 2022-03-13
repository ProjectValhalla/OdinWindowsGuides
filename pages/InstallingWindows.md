# Installing Windows 11
🔙 Back to [Windows Installation](https://github.com/ProjectValhalla/OdinWindowsGuides/blob/main/pages/WindowsInstallation.md)


## Copying Installer Files :
Extract and copy all content inside `odin_windows_installer.7z` to USB Flash Drive.

## Preparing Windows Installation Image :

⚠️ Current `odin_windows_installer.7z` is only compatible with Windows 11 release.

To get ARM64 `install.wim` or `install.swm` you need to download from Microsoft server using [UUPDump](https://uupdump.net) or [UUPMediaCreator](https://github.com/gus33000/UUPMediaCreator).

Latest version of Windows 11 ARM64 that was tested working without too much problem is **22543.1000** and **22000.556**.

The Windows 11, version 22H2 Insider Preview **10.0.22572.100** are have some problem, like Settings can't be opened.

Download the Windows release using `UUPDump` or `UUPMediaCreator` to creating **ISO** image.

Extract the `install.wim` from ISO image:

![Extract install.wim](/images/extract_install_wim.jpg)

The USB Flash Drive is formatted in **FAT32** so the biggest file that can be copied to USB Flash drive is about 4GB.
If the `install.wim` is bigger than 4GB then it need to be converted to `install.swm` by using DISM tool.

here is the example command for splitting .wim file to .swm files:

```
Dism /Split-Image /ImageFile:E:\WindowsRelease\install.wim /SWMFile:E:\WindowsRelease\install.swm /FileSize:1000
```

Copy `install.wim` or `install.swm` to `/images/` folder in USB Flash Drive.

Plug to Odin and start the installation.