# Android环境搭建

## 工具  

* **JDK**  （jdk-8u144-windows-x64）
* **SDK**  
* **Android Studio**  （android-studio-bundle-162.4069837-windows）

## 安装步骤

### 1、JDK 安装  
根据安装对话框逐步安装，修改对应的安装目录即可；

### 2、安装 Android Studio  
根据安装对话框逐步安装，修改对应的安装目录即可；  

### 3、SDK 安装  
**两种方法**：  
1）已经打包好的sdk，可以直接解压放到某个目录，安装好Android Studio后通过PackageManager来引用sdk路径  
2）在安装Android Studio的过程中选择安装，如果有VPN那么可以直接选择这种安装，如果无法访问谷歌的服务器就选择第一种方式  


## 环境变量
### 1、java环境变量  
1）添加环境变量JAVA_HOME  
JDK的安装目录，如：D:\Java8\jdk   

2）修改环境变量path  
如：javac、java等
在后面增加  
%JAVA_HOME%\bin  
%JAVA_HOME%\jre\bin

### 2、android工具的环境变量  
1）添加环境变量ANDROID_HOME  
SDK的安装目录，如：D:\Android\sdk  
如：adb等  

### 3、修改环境变量path  
在后面增加  
%ANDROID_HOME%\platform-tools  
%ANDROID_HOME%\sdk\tools  


## 碰到的问题  
### 1、Android Studio修改安装目录后，提示安装路径有问题，不允许安装  
进行如下修改  
![](https://github.com/RamboTong/MobileDevelopment/blob/master/00Android%E5%BC%80%E5%8F%91%E7%8E%AF%E5%A2%83%E6%90%AD%E5%BB%BA/pic/as00.png) 

### 2、安装好Android Studio出现如下异常  
![](https://github.com/RamboTong/MobileDevelopment/blob/master/00Android%E5%BC%80%E5%8F%91%E7%8E%AF%E5%A2%83%E6%90%AD%E5%BB%BA/pic/as01.png)
 
直接点击取消即可。之后会提示安装component,其实就是安装sdk到默认路径，可以取消这次安装，因为sdk之前是安装好的。  

