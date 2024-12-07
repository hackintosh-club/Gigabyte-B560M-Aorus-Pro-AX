## 技嘉 B560M Aorus Pro AX 黑苹果 OpenCore EFI

![image](ScreenShot/JINGYUEB760I.png)

### [ENGLISH](https://github.com/hackintosh-club/JINGYUE-B760I-SNOW-DREAM-OpenCore)

### OpenCore

[OpenCore 1.0.3](https://github.com/acidanthera/OpenCorePkg)

### macOS

- macOS Monterey  12.x
- macOS Ventura     13.x
- macOS Sonoma    14.x
- macOS Sonoma    15.x

### 硬件

- 芯片组: : Intel Tiger Point B560
- Bios 版本: F8 08/31/2021
- 处理器: 英特尔10代 i5-10400F
- 内存: 光威 16GB(8GB*2) DDR4 3200Mhz
- 硬盘: 金士顿 SNV2S   500G  Windows
- 硬盘: 金士顿 SUV500 480G  MacOS
- 独显: 华硕 Radeon RX 6600 8GB GDDR6
- 声卡: 瑞昱 ALC897
- 有线网卡:  英特尔 Intel I225-V
- 无线网卡: 英特尔 Wi-Fi 6 AX200 160MHz

### BIOS设置

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

### 注意事项

 - 安装成功后必须使用  [OCAuxiliaryTools](https://github.com/ic005k/OCAuxiliaryTools) 生成你自己的 SMBIOS
 - 此EFI中的英特尔无线网卡驱动[itlwm.kext](https://github.com/OpenIntelWireless/itlwm/releases)适用于 MacOS 所有版本,连结WiFi请下载并使用[HeliPort.dmg](https://github.com/OpenIntelWireless/HeliPort/releases/download/v2.0.0-alpha/HeliPort.dmg).
- 英特尔无线网卡无法使用隔空投送等功能


### 联系我们

QQ群: 23304408

![image](ScreenShot/QRCode.png)



### 常用工具

- [Hackintool](https://github.com/headkaze/Hackintool) 
- [OCAuxiliaryTools](https://github.com/ic005k/OCAuxiliaryTools) AKA `OCAT`.
- [OpenCore Configurator](https://mackie100projects.altervista.org/opencore-configurator/) AKA `OCC`.
- [gibMacOS](https://github.com/corpnewt/gibMacOS) Build your own MacOS image.
- [ProperTree](https://github.com/corpnewt/ProperTree) Plist editor.