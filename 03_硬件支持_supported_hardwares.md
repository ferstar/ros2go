我们只能列出经过测试的型号，我们努力了但是还不行的型号。这个列表会经常更新。    
Will keep you posted.  

# 电脑型号支持列表：  
# Brand and Type of the PCs  

## 白名单：畅快玩耍   
## White list:  So Easy!  
### Lenovo  
### Dell  
### Thinkpad  
### MacBook Pro  
(before 2016)  
### HP
Omen    


## 灰名单：可以但是比较费劲或者还有部分问题
## Gray list：Need some special settings or still got some issues
Acer F15 (请询问售后ROS2GO的qq群， plz inquire ACER tech support)  
MacBookPro after 2016 请仔细阅读链接了解对新的MBP的支持情况。Checkout this https://github.com/Dunedan/mbp-2016-linux/blob/master/README.md （需要外接鼠标键盘，有发热问题。 need external mouse and keyboard, overheating）

## 黑名单：可能你完全无法进入HDD或者完全不能从ROS2GO启动
## Black list： Sorry that we cannot rewrite Ubuntu  

- Sony Vaio T13 before 2013 (不能进入HDD， cannot enter HDD)


# 网卡支持型号列表：  
# Type of wifi adapter supported：  

## 白名单：  
## White list：  
### rtl
rtl8188ee
rtl8188eu
rtl8192c
rtl8192ce
rtl8192cu
rtl8192de
rtl8192ee
rtl8192eu
rtl8192se
rtl8723ae
rtl8723be
rtl8723com
rtl8821ae
rtl8812au
rtl8822be

### mtk
mt7601
mt766u
mt7632u
mt7612u

### Intel
Wireless-AC 8260
Wireless-AC 3165
Wireless-AC 7265
Wireless-N 7265
Wireless-N 7265
Wireless-AC 3160
Wireless-AC 7260
Wireless-N 7260
Wireless-N 7260
Wireless-AC 7260
Advanced-N 6230
Wireless-N 1030
Wireless-N 130
Advanced-N 6235
Wireless-N 135
Wireless-N 105
Wireless-N 2200
Wireless-N 2230
Wireless-N 1000
Advanced-N 6205
Wireless-N 100
Wireless-N + WiMAX 6150
Advanced-N + WiMAX 6250
Ultimate-N 6300
Advanced-N 6200
WiFi Link 5100AGN
WiFi Link 5300AGN
WiFi Link 5350AGN
WiFi Link 5150AGN

### Broadcom
BCM4311
BCM4312
BCM4313
BCM4321
BCM4322
BCM43224
BCM43225
BCM43227
BCM43228

## 灰名单：
## Grey list：
- BCM 43142   
如果您只在BCM 43142型号网卡的电脑上使用ROS2GO，可以参考以下链接安装。 因为会影响到MacBook的网卡驱动，所以默认是没有安装的。

If you only use ROS2GO on a laptop with BCM 43142 wifi adapter, please do not hesitate to install the driver as the following link stated. However, it will affect MacBook wifi adapter and is not pre-installed.  

https://help.ubuntu.com/community/WifiDocs/Driver/bcm43xx#Switching_between_drivers

## 黑名单：
## Black list：
抱歉，我们不支持任何360的外接WiFi设备。
