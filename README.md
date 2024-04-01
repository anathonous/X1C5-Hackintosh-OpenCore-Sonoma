# macOS on Thinkpad X1 Carbon 5th Generation, Model 20HQ\*

[![macOS](https://img.shields.io/badge/macOS-Sonoma-A020F0.svg)](https://github.com/996icu/996.ICU/blob/master/LICENSE)
[![version](https://img.shields.io/badge/14.3.1-yellow)](https://github.com/996icu/996.ICU/blob/master/LICENSE)
[![BIOS](https://img.shields.io/badge/BIOS-1.66-red)](https://github.com/996icu/996.ICU/blob/master/LICENSE)
[![MODEL](https://img.shields.io/badge/Model-20K4*-red)](https://github.com/996icu/996.ICU/blob/master/LICENSE)
[![OpenCore](https://img.shields.io/badge/OpenCore-latest-green)](https://github.com/996icu/996.ICU/blob/master/LICENSE)
[![LICENSE](https://img.shields.io/badge/license-MIT-green.svg)](https://github.com/996icu/996.ICU/blob/master/LICENSE)

<img align="right" src="https://imgur.com/HdvMc8E.png" alt="macOS" width="300">

#### I am not responsible for any damages you may cause.


> ## SUMMARY:

*In short, x1c5-hackintosh is very stable and is currently my daily driver. I quad boot on this machine with Linux, FreeBSD, Windows, MacOS and all provide an enjoyable experience. Overall macOS works fine on this machine.*


> ## NEEDED:

A macOS machine is needed to: Create install drives. A usb key for Opencore and a usb key for macOS Installer.


> ## INSTALL:
Create a bootable EFI drive. Copy over the OpenCore files.<br>
Create a bootable macOS install. On a Mac. Download 14.3.1. Using gibMacos. Install the InstallAssistant.pkg. Show files on macOS Install Sonoma.app. createinstall media on a 32GB flashdrive. <br>
Install Sonoma 14.3.1. May take several reboots. <br>
Done.<br>

## UPDATE
If you edit your opencore config.efi and change SecureBootModel from Defaults to Disabled. You can rerun the macOS Install Sonoma.app for 14.4.1 and it will update to Sonoma 14.4.1. You will need to change it back and update Airportitlwm.kext though. As they do not Jive. Download the [latest](https://github.com/OpenIntelWireless/itlwm/releases/download/v2.3.0-alpha/AirportItlwm-Sonoma14.4-v2.3.0-DEBUG-alpha-e886ebb.zip).

> ## MY SPECIFICATIONS:

Refer to [x1c5-Platform_Specifications](https://github.com/B0hrer/thinkpad-x1c5-hackintosh/blob/master/docs/ThinkPad_X1_Carbon_5th_Gen_Spec.PDF) for possible stock ThinkPad X1 5th Gen configurations.

| Processor Number                                                                                                                   | # of Cores | # of Threads | Base Frequency | Max Turbo Frequency | Cache | Memory Types | Graphics      |
| :--------------------------------------------------------------------------------------------------------------------------------- | :--------- | :----------- | :------------- | :------------------ | :---- | :----------- | :------------ |
| [i5-6300U](https://ark.intel.com/content/www/us/en/ark/products/88190/intel-core-i5-6300u-processor-3m-cache-up-to-3-00-ghz.html) | 2          | 4            | 2.4 GHz        | 3.0 GHz             | 3 MB  | LPDDR3-1866  | Intel UHD 520 |

**Peripherals:**

```
Two USB 3.1 Gen 1 (Right USB Always On)
Two USB 3.1 Type-C Gen 2 / Thunderbolt 3 (Max 5120x2880 @60Hz)
HDMI 1.4b (Max 4096x2160 @30Hz)
Ethernet via ThinkPad Ethernet Extension Cable Gen 2: I219-LM Ethernet (vPro)
No WWAN
TrackPoint: PS/2
TrackPad: ELAN
```

**Display:**  
`14.0" (355mm) FHD IPS (1920x1080)`  
**Audio:**  
`CX11871 Audio Codec`  
**Thunderbolt:**  
`Intel JHL6540 (Alpine Ridge 4C) Thunderbolt 3 Bridge`

> ## Read These (References):

- [dortania Hackintosh guides](https://github.com/dortania)
- [The Vanilla Laptop Guide](https://fewtarius.gitbook.io/laptopguide/)
- Daliansky's [Hackintool tutorial](https://translate.google.com/translate?js=n&sl=auto&tl=en&u=https://blog.daliansky.net/Intel-FB-Patcher-tutorial-and-insertion-pose.html).
- [Getting Started with ACPI](https://khronokernel.github.io/Getting-Started-With-ACPI/)
- [WhateverGreen Intel HD Manual](https://github.com/acidanthera/WhateverGreen/blob/master/Manual/FAQ.IntelHD.en.md)

> ## OTHER x1c6-hackintosh REPOSITORIES:

[tylernguyen/x1c6-hackintosh](https://github.com/tylernguyen/x1c6-hackintosh)
[zhtengw/EFI-for-X1C6-hackintosh](https://github.com/zhtengw/EFI-for-X1C6-hackintosh)  
[Colton-Ko/macOS-ThinkPad-X1C6](https://github.com/Colton-Ko/macOS-ThinkPad-X1C6)  

> ## Credits and Thank You:

[@tylernguyen](https://github.com/tylernguyen/x1c6-hackintosh) for creating a great guide, which I could modify to work on th x1c5 and for the great README template I could copy for my repo  
[@stevezhengshiqi](https://github.com/stevezhengshiqi) for the one-key-cpufriend script.  
[@corpnewt](https://github.com/corpnewt) for CPUFriendFriend.  
[@xzhih](https://github.com/xzhih) for one-key-hidpi.  
