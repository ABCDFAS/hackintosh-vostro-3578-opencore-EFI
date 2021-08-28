# vostro 3578 黑苹果OC0.7.2 EFI

型号 vostro 3578

CPU：i5-8250U

内存： 16GB DDR4 2400MHZ

硬盘： 镁光256G SATA SSD
            英睿达mx500 500G SATA SSD

显卡： 核显UHD620
独立显卡Radeon 520无法驱动 已屏蔽

声卡 ALC236

网卡 BCM94360CS2 / Realtek RTL8168H/8111H PCI Express**

OC版本：0.7.2

## 目前驱动正常情况

声卡 applealc仿冒ID 16 耳机和外放都正常 ✅

核显 UHD620驱动成功 仿冒ID 591C0005解决闪屏问题 ✅

硬件加速 正常 FNCP 正常打开无闪退情况 ✅

Wi-Fi及以太网：更换免驱卡94360CS2 正常 ✅

USB定制 蓝牙 USB3.0 摄像头 正常 ✅

睡眠 Big Sur 以及Monterey（21A5304g）测试正常 ✅

触控板 i2C 多点手势 正常 ✅

电池信息显示 正常✅

## 需要注意的问题

1.若使用此EFI进行安装macOS Monterey 由于lilu未更新 本EFI已添加-lilubetaall

2.HDMI未进行测试 驱动成功失败未知


