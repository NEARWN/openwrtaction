云编译方法来自P3TERX，esirplayground

https://github.com/P3TERX/Actions-OpenWrt

https://github.com/esirplayground/AutoBuild-OpenWrt

编译源码使用

Lean's OpenWrt source https://github.com/coolsnowwolf/lede

替换源码中MOSDNS为以下源码

https://github.com/QiuSimons/openwrt-mos

https://github.com/sbwml/luci-app-mosdns

解除网易云音乐播放限制的 OpenWrt 插件使用源码

https://github.com/UnblockNeteaseMusic/luci-app-unblockneteasemusic

xiaomi redemi ac2100通过这样的方式打开无线，以下方法都建议使用。

脚本
在系统-启动项-本地启动脚本 插入 /sbin/mtkwifi up 在 exit 0 前面。

如下所示

/sbin/mtkwifi up

exit 0

计划任务

在系统-计划任务中填入 0 * * * * /sbin/mtkwifi up 计划任务。

