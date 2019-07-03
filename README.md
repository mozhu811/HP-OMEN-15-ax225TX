# HP-OMEN-15-ax225TX

:computer: i5-7300HQ, GTX1050Ti 惠普暗影精灵2Pro黑苹果efi, HP OMEN 15-ax225TX hackintosh clover efi.  

使用该efi可以顺利安装macOS mojave 10.14.5.  
## 众所周知的问题：
+ HDMI外接显示器没法用
+ 独显没法驱动
+ 触摸板支持的手势比较少
+ 无线网卡无法驱动，当然我已经更换了网卡Broadcom BCM94352z开机即用

## 在本人的机器上出现的比较在意的问题（没提到即表示本人觉得不影响使用的问题或暂未发现）
+ 以上提到的问题（无线网卡除外）
+ 电源管理（不接入电源的时候，电源一直都是100%，不掉电，永动机？）
+ 键盘无法调节亮度，但显示器偏好设置中可以设置
+ 从Windows`重启`进入macOS声卡无法正常工作

其他问题待使用发现，若有以上问题解决方案欢迎提出。

若进入系统扬声器无法使用，可以使用[Hackintool](http://headsoft.com.au/download/mac/Hackintool.zip)来更新最新的lilu和AppleALC驱动