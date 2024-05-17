# Fx-aqgf

福建信息职业技术学院安全攻防利用web漏洞一件获取Key并自动提交

## 当前版本 V1.2.1

v1.2.1
加入了自定义模式
修复了部分bug

v1.1.8
加入了重点信息高亮显示

v1.1.2
加入了对命令行自动提交的支持
修复了部分bug

v1.1
将ssh登录获取key方式改为使用WebShell
加入了浏览器自动化的支持

v1.0
对福建信息职业技术学院攻防演练平台的key获取脚本诞生

## 使用教程

### 第一步：下载本项目选最新版压缩包

下载链接：https://github.com/Azizi030/Fx-aqgf/releases

### 第二步：对下载的压缩包解压缩

![image](https://github.com/Azizi030/Fx-aqgf/blob/main/images/%E4%BD%BF%E7%94%A8%E6%95%99%E7%A8%8B01.png?raw=true)

### 第三步：鼠标连续点击“双击运行.bat”两次启动程序

![image](https://github.com/Azizi030/Fx-aqgf/blob/main/images/%E4%BD%BF%E7%94%A8%E6%95%99%E7%A8%8B02.png?raw=true)

### 第四步：按照需求参考图片输入参数

![image](https://github.com/Azizi030/Fx-aqgf/blob/main/images/%E4%BD%BF%E7%94%A8%E6%95%99%E7%A8%8B03.png?raw=true)

### PHPSESSID获取教程

各个浏览器都有轻微区别，这里简单举几个例子

火狐：登录平台->按下F12打开浏览器开发者工具->存储->Cookie->https://[ip]->PHPSESSID->复制他的值

Edge：登录平台->按下F12打开浏览器开发者工具->应用程序->存储->Cookie->https://[ip]->PHPSESSID->复制他的值

![images](https://github.com/Azizi030/Fx-aqgf/blob/main/images/PHPSESSID%E8%8E%B7%E5%8F%96%E6%95%99%E7%A8%8B.png?raw=true)

### 自定义模式使用教程

在输入验证码时在任意位置带上"+1"即可开启自定义URL模式

自定义URL格式

例如我需要往http://[ip]:8000/WebShell.php发送数据包

![images](https://github.com/Azizi030/Fx-aqgf/blob/main/images/%E8%87%AA%E5%AE%9A%E4%B9%89%E6%A8%A1%E5%BC%8F%E4%BD%BF%E7%94%A8%E6%95%99%E7%A8%8B.png?raw=true)





