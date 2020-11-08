# acer-s40-51-efi
宏碁蜂鸟FUN黑苹果efi分享

适用于Acer-s40-51（宏碁蜂鸟FUN）（资源来源于网友）
1，蓝牙可以关闭
2，可以实现关机断电
3，可以使用无线连接网络
   下载'itlwmx-v1.0.0-DEBUG-alpha-098b6a8.zip'这个驱动文件，解压出来后将itlwmx.kext放到clover/kexts/other下（此efi已有）
   安装heliport.dmg（这个是WiFi管理软件，可以试着给这个软件打开登陆自启动，开机就自动连上WiFi了）
4，添加了手机usb共享网络的驱动
5，提取efi的系统版本为10.15.6
6，显卡无法驱动（屏蔽了）

内容基于nsrlive/acer_s40_51上修改
