# ADB命令  
https://juejin.im/post/5b5683bcf265da0f9b4dea96  
### 1.使用wifi连接adb命令失败的话可以尝试以下步骤  
- 第一步：Android设备开启USB调试，并且通过USB线连接到电脑  
- 第二步：在终端执行以下命令”adb tcpip 5555“  
- 第三步：在终端执行以下命令”adb connect 172.20.10.10“(172.20.10.10为Android设备的IP地址)。此时拔出USB线，应该就可以adb通过wifi调试Android设备  
### 2.当adb连接了多个设备时，指定其中一个设备进行操作  
adb -s <serial number> 命令  
在设备前加入-s  
### 3.使用adb命令把文件从设备中发送到电脑上  
adb pull <文件路径> <电脑路径>        文件路径和电脑路径中有一个空格  
### 4.中断终端当前进程  

  
