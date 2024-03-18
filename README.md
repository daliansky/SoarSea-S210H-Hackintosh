# SoarSea-S210H-Hackintosh

![release version](https://img.shields.io/github/v/release/daliansky/SoarSea-S210H-Hackintosh?style=for-the-badge)  [![OpenCore version](https://img.shields.io/badge/OpenCore-0.9.9-informational.svg)](https://github.com/acidanthera/OpenCorePkg) ![MacOS version](https://img.shields.io/badge/Sonoma-14.4-informational.svg)![MacOS version](https://img.shields.io/badge/Ventura-13.6.5-informational.svg) [![MacOS version](https://img.shields.io/badge/Monterey-12.7.4-informational.svg)](https://www.apple.com/macos) [![MacOS version](https://img.shields.io/badge/Bigsur-11.7.10-informational.svg)](https://www.apple.com/macos)

[![S210H](./ScreenShots/S210H_taobao.png)](https://item.taobao.com/item.htm?id=693991506304)

## 电脑配置

|     规格      |                           详细信息                           |
| :-----------: | :----------------------------------------------------------: |
|   电脑型号    |                        SoarSea S210H                         |
|   操作系统    | macOS `Sonoma` / `Ventura` /  `Monterey` / `Big Sur` / `Catalina` / `Mojave` |
|    处理器     |               英特尔 酷睿 i9-10980HK / i9-10885H /i9-9980HK 8核16线程<br />i7-10870H 8核16线程<br />i7-10750H 6核12线程               |
|     内存      |                      64 GB DDR4 3200MHz                      |
|    硬盘1/2    | WD SN570 1TB/HS-SSD-C2000 2TB<br />支持双NVMe或NVMe+SATA SSD或双SATA SSD<br />最高支持 4TB+4TB双NVMe固态组合 |
|    硬盘/3     |                 可接SATA 2.5寸硬盘/SSD(7mm)                  |
|     显卡      |                    Intel UHD Graphics 630                    |
|   视频输出    | DP 1.2 x 1 (Support 4K@60Hz)<br />HDMI 2.0a x1 (Support 4K@60Hz) |
|     声卡      |        Cmedia HS-100B **USB Audio Device** `alcid=11`        |
|   无线网卡    | m.2 NGFF插槽，已更换为[BCM94360Z3](https://blog.daliansky.net/uploads/WeChatandShop.png) |
|   有线网卡1   | **Realtek RTL8125B PCI Express 2.5 Gigabit Ethernet**(i9)<br />**Realtek RTL8168H/8111H PCI Express Gigabit Ethernet**(i7) |
|   有线网卡2   |         **Intel I219 PCI Express Gigabit Ethernet**          |
| 体积尺寸/重量 |                 143mm x 136mm x 64mm / 1050g                 |
|     电源      |                19V x 4.73A 90W 5.5mm x 2.5mm                 |

## 更新日志

- 3-18-2024
  - 更新 `IOSkywalkFamily.kext` 到 `v1.1.0`
  - `Sonoma` 如果想更新到 `14.4` 请务必先更新 `EFI` ，然后再安装 [OCLP](https://pan.daliansky.net/APPS/OCLP/OCLP.md)，重启后，再升级到 `14.4` 否则会出现 `WIFI` 无法启用的问题
- 11-1-2023
  - Release `v2.0.0`
  - 更新 `OpenCore` `v0.9.5`
  - 支持 `Sonoma` 安装使用，[OCLP教程](https://blog.daliansky.net/OCLP.html)
- 3-15-2023
  - Release `v1.2.0`
  - 更新 `OpenCore` `v0.9.0`
- 2-15-2023
  - Release `v1.1.0`
  - 更新 `OpenCore` `v0.8.9`
- 11-25-2022
  - Release `v1.0.0`
  - 更新 `OpenCore` `v0.8.6`
  - 初始版本

## 截屏



![OC](./ScreenShots/OC.png)

![S210H_About](./ScreenShots/S210H_About_Sonoma.png)

![0Hackintool](./ScreenShots/0Hackintool.png)

![1Hackintool_Misc](./ScreenShots/1Hackintool_Misc.png)

![2Hackintool_Bootloader](./ScreenShots/2Hackintool_Bootloader.png)

![3Hackintool_NVRAM](./ScreenShots/3Hackintool_NVRAM.png)

![4Hackintool_Kexts](./ScreenShots/4Hackintool_Kexts.png)

![5Hackintool_Displays](./ScreenShots/5Hackintool_Displays.png)

![6Hackintool_Audio](./ScreenShots/6Hackintool_Audio.png)

![7Hackintool_USBPorts](./ScreenShots/7Hackintool_USBPorts.png)

![8Hackintool_PM](./ScreenShots/8Hackintool_PM.png)
