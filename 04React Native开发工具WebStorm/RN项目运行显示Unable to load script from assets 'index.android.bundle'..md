# RN项目运行显示Unable to load script from assets 'index.android.bundle'.

## 操作方式  
WebStorm执行运行run-androd  

## 报错详情  
![](https://github.com/RamboTong/MobileDevelopment/blob/master/04React%20Native%E5%BC%80%E5%8F%91%E5%B7%A5%E5%85%B7WebStorm/pic/ws23.png)  

## 分析  
asset文件夹目录缺失，并且缺少bundle文件  

## 解决方法  
1、到项目目录新增assets文件夹 
项目名称\android\app\src\main   

2、执行如下命令  
react-native bundle --platform android --dev false --entry-file index.android.js --bundle-output android/app/src/main/assets/index.android.bundle --assets-dest android/app/src/main/res  

执行成功后,assets文件夹下会生产两个bundle文件  
![](https://github.com/RamboTong/MobileDevelopment/blob/master/04React%20Native%E5%BC%80%E5%8F%91%E5%B7%A5%E5%85%B7WebStorm/pic/ws24.png)

