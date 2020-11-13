# AMD Ryzen Hackintosh

forked from https://github.com/kdbaustert/ryzen-hackintosh

**macOS version**: 10.15.6  
**OpenCore version**: 0.6.3 


## Specification
| Component        | Model                                  |
| ---------------- | -------------------------------------- |
| CPU              | AMD Ryzen 3 2200g                      |
| MotherBoard      | GIGA x470 aorus gaming                 | 
| OS Disk          | Samsung 850 evo 250 GB                 |
| RAM              | 1 X 16gb Corsair Vengeance LPX 3000    |
| GPU              | Sapphire Radeon R9 280 3GB             |
| WiFi & Bluetooth | Fenvi FV-T919   ( shipping )           |
| Audio            | Alc1220                                |
| Audio            | Sound blaster x g6  ( shipping )       |

## Patches, Drivers & Kexts

- [Patchs] AMD_Vanilla] (https://github.com/AMD-OSX/AMD_Vanilla)
- [Driver] OpenRuntime
- [Driver] OpenCanopy
- [Driver] HfsPlus
- [Kext] Lilu
- [Kext] WhateverGreen
- [Kext] AppleALC
- [Kext] SmallTreeIntel82576
- [Kext] AMDRyzenCPUPowerManagement
- [Kext] AppleMCEReporterDisabler

## Working

- [x] iCloud
- [x] Handoff
- [] AirDrop
- [] Bluetooth
- [] WiFi
- [x] Ethernet
- [x] Sleep with hibernate mode 0

## Known Issues
- iMessager could not login
- Apple ID could not finish login
- With ALC1220, Media players like Quick time and Apple music have noticeable dropping / popping issues; things like Browsing YouTube are fine. 
