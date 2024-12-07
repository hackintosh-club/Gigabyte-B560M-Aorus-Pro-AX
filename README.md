## Gigabyte B560M Aorus Pro AX Hackintosh OpenCore EFI

![image](ScreenShot/JINGYUEB760I.png)

### [简体中文](README.zh_CN.md)

### OpenCore

[OpenCore 1.0.3](https://github.com/acidanthera/OpenCorePkg)

- macOS Monterey  12.x
- macOS Ventura    13.x
- macOS Sonoma   14.x
- macOS Sequoia   15.x

### Hardware

- Motherboard: Intel Tiger Point B560
- Bios Version: F8 08/31/2021
- CPU: Intel 10th i5-10400F
- RAM: Gloway 16GB(8GB*2) DDR4 3200Mhz
- SSD: KINGSTON SNV2S   500G  Windows
- SSD: KINGSTON SUV500 480G  MacOS
- GPU: ASUS Radeon RX 6600 8GB GDDR6
- Audio: Realtek ALC897
- LAN: Intel I225-V
- WIFI: Intel Wi-Fi 6 AX200 160MHz

### Notes

 - Use [OCAuxiliaryTools](https://github.com/ic005k/OCAuxiliaryTools) build your SMBIOS.
 - Intel WiFi driver [itlwm.kext](https://github.com/OpenIntelWireless/itlwm/releases) in this EFI is applicable MacOS 12-15. Connect WiFi Please download [HeliPort.dmg](https://github.com/OpenIntelWireless/HeliPort/releases/download/v2.0.0-alpha/HeliPort.dmg).
- Intel Not Supported Airdrop.

### Bios Setup

```
 |-- CFG Lock ：Disabled
 |-- Fast Boot ：Disabled
 |-- CSM ：Disabled
 |-- Fast Boot ：Disabled
 |-- VT-D ：Enabled
 |-- Above 4G ：Enabled
 |-- Re-Size BAR Support ：Disabled
 |-- IOAPIC 24-119 Entries ：Disabled
 |-- XHCI Hand-off ：Enabled   (USB)   
 |-- SATA MODE ：AHCI
 |-- Secure Boot ：Disabled 
```



### Contact Us

QQ Group: 23304408

![image](ScreenShot/QRCode.png)


### Tools

- [Hackintool](https://github.com/headkaze/Hackintool) 
- [OCAuxiliaryTools](https://github.com/ic005k/OCAuxiliaryTools) AKA `OCAT`.
- [OpenCore Configurator](https://mackie100projects.altervista.org/opencore-configurator/) AKA `OCC`.
- [gibMacOS](https://github.com/corpnewt/gibMacOS) Build your own MacOS image.
- [ProperTree](https://github.com/corpnewt/ProperTree) Plist editor.
