# ROG-M10H-QTJ1-OpenCore
如你所见，这是一个m10h+qtj1+uhd630的opencore引导

---
配置
| 配件  |型号|
| --- | --- |
|   主板  | ROG Maximum X Hero (WiFi-AC)    |
|   CPU  |    QTJ1 （10980HK ES）  |
|   显卡  |   INTEL UHD630  |
| 启动盘 |三星PM951A  |
|系统|macOS Monterey 12.1|
|无线网卡|博通BCM9260CS2|

---

***本EFI只保证能在本人电脑上正常使用
对于下载下来的efi需要微调***

1. 本人未使用前置type-c接口，所以有需要的应重新定制usb
2. 本人目前没能实现对该EFI的完美唤醒
3. 因有During架构的独立显卡存在，本人已将启动项添加了"-wegnoegpu"，如果有需要使用独立显卡的用户请删除此启动项
