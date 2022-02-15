# T480-OpenCore-Hackintosh

<img align="right" src="https://github.com/EETagent/T480-OpenCore-Hackintosh/raw/master/Other/README_Resources/ThinkPad.gif" alt="T480 macOS" width="430">


## Introduction

<details>
<summary><strong>Hardware</strong></summary>
<br>


| Category  | Component                         | Note                                                         |
| --------- | --------------------------------- | ------------------------------------------------------------ |
| CPU       | Intel Core i7-8550U               | 20L50000MC                                                   |
| GPU       | Intel UHD 620                     |                                                              |
| SSD       | 500GB   | Replaced cursed PM 981 which stil doesn't work reliably      |
| Memory    | 8+16GB DDR4 2400Mhz               |                                                              |
| Battery   | Dual battery                      |                                                              |
| Camera    | 720p Camera                       |                                                              |
| Wifi & BT | WIFI real mac                          |                                                              |
| Input     | PS2 Keyboard & Synaptics TrackPad | [YogaSMC](https://github.com/zhen-zen/YogaSMC) for media keys like microphone switch, etc. PrtSc is mapped as F13. |

</details>  

<details>

<summary><strong>Main software</strong></summary>
<br>

| Component      | Version        |
| -------------- | -------------- |
| macOS Monterey | 12.2.1 (21D62) |
| macOS Big Sur  | 11.6 (20G165)  |
| OpenCore       | v0.7.8         |

</details>

## Status

<details>  


<summary><strong>What's working ✅</strong></summary>

- [x] Battery percentage
- [x] Bluetooth - Broadcom BCM1820A
- [x] Boot chime
- [x] Boot menu `OpenCanopy` 
- [x] CPU power management / performance `Now on par with Windows without XTU undervolt.`
- [x] FireVault 2 `No config.plist changes needed` 
- [x] GPU UHD 620 hardware acceleration / performance 
- [x] HDMI `Closed and opened lid. With audio.`
- [x] iMessage, FaceTime, App Store, iTunes Store. **Generate your own SMBIOS**
- [x] Intel I219V Ethernet port
- [x] Keyboard `Volume and brightness hotkeys. Another media keys with YogaSMC.`
- [x] Microphone `With keyboard switch using ThinkPad Assistant.`
- [x] Realtek® ALC3287 ("ALC257") Audio
- [x] SD card reader `Fortunately, USB connected.`
- [x] Sidecar wired `Works with 15,2 SMBIOS.`
- [x] Sleep/Wake 
- [x] TouchPad `1-5 fingers swipe works. Emulate force touch using longer and more voluminous touch.`
- [x] TrackPoint  `Works perfectly. Just like on Windows or Linux.`
- [x] USB Ports `USB Map is different for devices with Windows Hello camera.`
- [x] Web camera
- [x] Wifi - Broadcom BCM1820A
- [x] DRM `Widevine, validated on Firefox 82. WhateverGreen's DRM is broken on Big Sur`
- [x] Windows 11 boot from OC boot menu

</details>  

<details>  

<summary><strong>What's not working ⚠️</strong></summary>

- [ ] Fingerprint reader  `There is finally after many years working driver for Linux (python-validity), don't expect macOS driver any time soon.`

- [ ] PM 981 `Still unstable.`

- [ ] Sidecar wireless `If you want to use this feature, buy a compatible Broadcom card!`

</details>  

<details>  

<summary><strong>Need help</strong></summary>

- [ ] Thunderbolt to DP  `Can't recognize 4k display, but is normal under windows booting via OC.`

</details>  

