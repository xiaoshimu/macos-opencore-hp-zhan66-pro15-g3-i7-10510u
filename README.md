# hp-zhan-66-pro-15-g3
The repository provides OpenCore configuration files for hp-zhan-66-pro-15-g3.

# bigsur说明

bios升级到最新版本。不然可能电池失效

有限网卡驱动版本为RealtekRTL8111 V2.2.2，3.0驱动有点问题

触摸板驱动为VoodooI2C-2.4.4，高版本无法适用触摸板

网卡为原装的AX201，我的DW1820A有点问题，型号为CN-08PKF4，不是这个型号的自己试试

# 电脑配置
电脑型号：HP ZHAN 66 Pro 15 G3 笔记本电脑   
操作系统：macOS Catalina 10.15.5(19F96)   
处理器：英特尔 Core i7-10510U @ 1.80GHz 四核   
主板：惠普 86A8 ( I/O - 0284 for Intel 400 Series 芯片组 Family On-Package Platform Controller Hub )   
内存：16 GB ( DDR4 2666MHz )   
硬盘：英特尔  SSDPEKNW512G8H (固态硬盘)   
显卡：英特尔 UHD Graphics   
显示器：LG LGD062E ( 15.5 英寸  )   
声卡：英特尔 ALC236   
网卡：英特尔 AX201   
网卡：瑞昱 RTL8168/8111/8112 Gigabit Ethernet Controller / 惠普   
   
# 功能说明：   
CPU：已睿频  
显卡：仿冒UHD630   
网卡：有线网卡   
触摸板：HID支持   
电池显示：可以   
显示器亮度：可以   
蓝牙： 已支持  
SD卡：已支持  
USB：已修复  
声卡：OK   

显卡：Nvidia GeForce MX250   已屏蔽  
指纹：不支持。 
WIFI：不支持。   

配置教程：https://dortania.github.io/vanilla-laptop-guide/OpenCore/config-laptop.plist/coffee-lake-plus.html#platforminfo
注意：自己的机器请修改为自己的三码，然后登陆APPLE账号
工具地址：https://github.com/corpnewt/GenSMBIOS
