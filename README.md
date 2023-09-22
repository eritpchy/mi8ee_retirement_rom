# mi8ee_retirement_rom
XiaoMi Mi 8 Explore Edition, Mi 8 EE, ursa 养老固件方案

1. 刷机工具: [MiFlash2020-3-14-0.rar](https://xiaomirom.com/download-xiaomi-flash-tool-miflash/)
2. 刷入twrp: [recovery-TWRP-3.3.2B-0301-XIAOMI8EE-CN-wzsx150.img](./recovery-TWRP-3.3.2B-0301-XIAOMI8EE-CN-wzsx150.img)
3. 进入twrp刷入EU版固件, 女巫内核刷不进, 目前只发现这个可以开启f2fs, [点击链接](https://sourceforge.net/projects/xiaomi-eu-multilang-miui-roms/files/xiaomi.eu/MIUI-STABLE-RELEASES/MIUIv12/), 搜索 xiaomi.eu_multi_MI8Explorer
4. 转换Data和Cache分区成f2fs, TWRP --> 清除 --> 高级清除 --> 先选一个分区 --> 转换分区格式 --> 选择f2fs
5. 刷入[Patch-wayne-f2fs-any-rom.zip](./Patch-wayne-f2fs-any-rom.zip)模块
6. 刷入[f2fs-optimize.zip](./f2fs-optimize.zip), 这个是优化模块, 实测可以提升25%左右的跑分
7. 开机, 大约需要10分钟左右.
8. 使用[mipay-extract](https://github.com/kooritea/mipay-extract) 从国行ROM([下载地址](https://xiaomirom.com/rom/mi-8-explorer-ursa-china-fastboot-recovery-rom/#%E4%B8%8B%E8%BD%BD-%E5%B0%8F%E7%B1%B3-8-%E9%80%8F%E6%98%8E%E6%8E%A2%E7%B4%A2%E7%89%88-%E7%A8%B3%E5%AE%9A%E7%89%88-recovery-%E5%8D%A1%E5%88%B7%E5%8C%85))提取本地化资源, 进TWRP刷入
9. Enjoy.

附: 别买特殊版! 别买特殊版! 别买特殊版!

## 若本文对您有帮助, 欢迎赞助👍
![donate.png](donate.png)