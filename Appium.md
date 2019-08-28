## 一、Windows上的Appium解决方案  
### 1.Appium新手教程  
http://www.testclass.net/appium/  
### 2.Appium使用Python编写脚本的教程  
https://selenium-python-zh.readthedocs.io/en/latest/installation.html  
### 3.使用adb命令定位当前的app的appPackage和appActivity  
Windows环境下：adb shell dumpsys activity | findstr mFocusedActivity  
Linux环境下（即mac）：adb shell dumpsys activity | grep mFocusedActivity  
adb devices命令识别不到模拟器的话，用SDK的adb.exe替换掉虚拟机安装目录下的adb.exe  
### 4.Appium常见的一些报错及解决办法  
https://blog.csdn.net/xl_lx/article/details/78717898  
### 5.在编写测试用例时，如果总是出现定位失败的问题的话，在执行动作前等待几秒待页面完全加载完成就可以了  
time.sleep(5)  
## 二、MAC上的Appium解决方案  
### 1.Appium官网使用homebrew安装方法  
```
> brew install node      # get node.js 

> npm install -g appium  # get appium 

> npm install wd         # get appium client 

> appium &               # start appium
```
mac上安装如果提示没有权限，在命令行前➕sudo 
## 三、常用 Server Argument 讲解  
```
此处有表哥占位
```
例如：
```
$ appium --address 0.0.0.0 --port 4723 --log "C:\appium.log" --log-timestamp --local-timezone --session-override
```
若你使用 mac ，请把日志位置从 "C:\appium.log" 改为 "~/appium.log"  
## 四、Desired Capabilities参数配置及含义  
```
此处有表格占位
```
以上为部分常用配置，从appActivity开始为Android特有的，iOS此处暂时不做考虑，详细的请参考：https://www.cnblogs.com/wysk/p/7346659.html  
## 五、Desired Capabilities使用  



