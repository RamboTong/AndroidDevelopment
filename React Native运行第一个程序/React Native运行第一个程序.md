# React Native运行第一个程序
> 前提是React Native环境已经搭建完成

## 目的  
创建和运行Reac Native项目。如:HelloWorldRN  

## 步骤  
### 1、初始化RN 项目，HelloWorldRN  
执行命令:react-native init HelloWorldRN  

期间会安装jest

创建项目成功后:  


### 2、运行项目
2.1 查看当前连接的设备  
执行命令:adb devices    

2.2 切换到项目目录，如C:\Users\tong_\HelloWorldRN  
执行命令: npm install

2.3 运行程序到设备上  
执行命令:react-native run-android （device name）

期间会下载和解压gralde


还会下载一些其他构建工具  

在build期间，node会构建module，会弹出node的命令框  
