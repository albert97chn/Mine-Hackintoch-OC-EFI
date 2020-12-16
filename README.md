黑苹果 小米游戏本2019 OpenCore 引导  
*Hackintoch-Migaming Laptop 2019-OpenCore-EFI*

测试机型  
小米游戏本 15.4寸 2019 I7-9750H RTX2060  
*由于硬件相差很小，理论同支持2018款及以前的小米游戏本。*  
测试版本  
macOS 11.1 BigSur With OpenCore 0.6.4 

主要硬件
- 处理器  
Intel(R) Core(TM) i7-9750H CPU @ 2.60GHz 驱动正常 已解锁多档睿频 CPU温度传感器正常工作。
- 核心显卡  
Intel(R) UHD Graphics 630 驱动正常，支持解锁HIDPI （原生显示屏为1080P，也没有外接分辨率更高显示器，默认没开启，需要的可以详情一键开启HIDPI）。
- 声卡  
Realtek High Definition Audio 已仿冒内建，极低概率(F≤5%)出现开机声音无驱动，重启即可恢复。
- 有线网卡  
Realtek Gaming GbE Family Controller RTL8118AS 已驱动正常使用。
- 无线网卡  
Intel(R) Wireless-AC 9560 160MHz 已驱动原生Wi-Fi，极低概率(F≤5%)出现无法驱动原生Wi-Fi，暂无法隔空投送，后续等待AirportItlwm驱动版本持续更新。
- 蓝牙模块  
英特尔(R) 无线 Bluetooth(R) AC9560 已驱动原生蓝牙，支持传输文件、连接蓝牙设备、正常控制AirPods、使用蓝牙连网。

其他
- USB Composite Device 已驱动自带4个USB3.1接口，因为2019款阉割Type-C接口，未知是否支持旧款Type-C。
- 内建 HID Keyboard Device 已驱动，除macOS原本不支持按键外可正常输入，可使用Fn组合键，疾速风扇按键可用。
- 内建 键盘小米功能键无作用，开机键无法睡眠或关机。
- 内建 触摸板已驱动 支持macOS原生手势，不支持压力感应。
- 调节屏幕亮度功能正常，支持控制中心调节和Fn组合键调节。
- 睡眠功能正常，支持手动睡眠、电池计划睡眠、盒盖睡眠，唤醒正常支持开机键唤醒。
- 电池及适配器驱动正常，支持电量显示、电池健康、网络唤醒、电能小憩。
- 风扇传感器无法驱动，无法检测转速。但由于是Bios直驱，CPU高温下会自动提高风扇转速。
- SD读卡器无法内建驱动。


