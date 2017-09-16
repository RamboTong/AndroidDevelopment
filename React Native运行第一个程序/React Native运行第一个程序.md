# React Native运行第一个程序
> 前提是React Native环境已经搭建完成

## 目的  
创建和运行Reac Native项目。如:HelloWorldRN  

## 步骤  
### 1、初始化RN 项目，HelloWorldRN  
执行命令:react-native init HelloWorldRN  
![](https://github.com/RamboTong/AndroidDevelopment/blob/master/React%20Native%E8%BF%90%E8%A1%8C%E7%AC%AC%E4%B8%80%E4%B8%AA%E7%A8%8B%E5%BA%8F/pic/rn05.png)
  
期间会自动安装jest  
![](https://github.com/RamboTong/AndroidDevelopment/blob/master/React%20Native%E8%BF%90%E8%A1%8C%E7%AC%AC%E4%B8%80%E4%B8%AA%E7%A8%8B%E5%BA%8F/pic/rn06.png)
  

创建项目成功后:  
![](https://github.com/RamboTong/AndroidDevelopment/blob/master/React%20Native%E8%BF%90%E8%A1%8C%E7%AC%AC%E4%B8%80%E4%B8%AA%E7%A8%8B%E5%BA%8F/pic/rn07.png)  


### 2、运行项目
2.1 查看当前连接的设备  
执行命令:adb devices   
![](https://github.com/RamboTong/AndroidDevelopment/blob/master/React%20Native%E8%BF%90%E8%A1%8C%E7%AC%AC%E4%B8%80%E4%B8%AA%E7%A8%8B%E5%BA%8F/pic/rn08.png)   
  
2.2 切换到项目目录，如C:\Users\tong_\HelloWorldRN    


2.3 运行程序到设备上  
执行命令:react-native run-android （device name）
期间会下载和解压gralde  
![](https://github.com/RamboTong/AndroidDevelopment/blob/master/React%20Native%E8%BF%90%E8%A1%8C%E7%AC%AC%E4%B8%80%E4%B8%AA%E7%A8%8B%E5%BA%8F/pic/rn09.png)  

还会下载一些其他构建工具 ,都是自动下载的 
  
在build后，会弹出node的命令框  
![](https://github.com/RamboTong/AndroidDevelopment/blob/master/React%20Native%E8%BF%90%E8%A1%8C%E7%AC%AC%E4%B8%80%E4%B8%AA%E7%A8%8B%E5%BA%8F/pic/rn10.png)  

构建成功后，会运行程序到设备上  
![](https://github.com/RamboTong/AndroidDevelopment/blob/master/React%20Native%E8%BF%90%E8%A1%8C%E7%AC%AC%E4%B8%80%E4%B8%AA%E7%A8%8B%E5%BA%8F/pic/rn11.png)


2.4运行效果  
![](https://github.com/RamboTong/AndroidDevelopment/blob/master/React%20Native%E8%BF%90%E8%A1%8C%E7%AC%AC%E4%B8%80%E4%B8%AA%E7%A8%8B%E5%BA%8F/pic/rn13.PNG)

## 碰到的问题
1、react-native run-android执行失败，如下:  
![](https://github.com/RamboTong/AndroidDevelopment/blob/master/React%20Native%E8%BF%90%E8%A1%8C%E7%AC%AC%E4%B8%80%E4%B8%AA%E7%A8%8B%E5%BA%8F/pic/rn12.png)  

因为npm没有install，执行上面的命令需要在项目的根目录下执行，如2.2步骤  

