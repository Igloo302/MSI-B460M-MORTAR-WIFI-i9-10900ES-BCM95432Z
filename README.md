# MSI-B460M-MORTAR-WIFI-i9-10900ES-BCM95432Z

## 黑苹果信息
macOS 20,2

Ventura 13.4

OpenCore 0.9.2


## 硬件配置

| 配置 | 型号 |
| ---- | ---- |
| CPU | Intel i9 10900ES |
| 主板 | 微星 MSI MAG B460M MORTAR WiFi|
| 显卡 | 蓝宝石 RX 590 8G | 
| WiFi + 蓝牙 | BCM95432Z | 

## 说明

### USB定制

使用了[Spectrelai/Hackintosh-B460M-MORTAR-WIFI: OpenCore EFI for MSI B460M MORTAR WIFI and RX 6600XT (github.com)](https://github.com/Spectrelai/Hackintosh-B460M-MORTAR-WIFI)制作的USBMap，关闭了后面网口边上的两个USB3.0接口

### WiFi和蓝牙

使用ngff接口BCM95432Z替换了板载的网卡，macOS 13.4有点问题，需要加两个NVRAM Keys，参考：[Update to Ventura 13.4 - bluetooth no longer works ( BCM94352HMB ) - OSx86 13.0 (Ventura) | InsanelyMac](https://www.insanelymac.com/forum/topic/356769-update-to-ventura-134-bluetooth-no-longer-works-bcm94352hmb/#comment-2805006)

## 致谢

[OpenCore Install Guide (dortania.github.io)](https://dortania.github.io/OpenCore-Install-Guide/)

[Spectrelai/Hackintosh-B460M-MORTAR-WIFI: OpenCore EFI for MSI B460M MORTAR WIFI and RX 6600XT (github.com)](https://github.com/Spectrelai/Hackintosh-B460M-MORTAR-WIFI)

