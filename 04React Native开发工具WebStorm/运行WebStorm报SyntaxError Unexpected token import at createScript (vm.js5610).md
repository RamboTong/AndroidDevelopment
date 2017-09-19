# 运行WebStorm报SyntaxError: Unexpected token import at createScript (vm.js:56:10)

## 执行方式
直接运行index.android.js

## 报错详情
"D:\RN\WebStorm 2017.2.4\bin\runnerw.exe" D:\Node\nodejs\node.exe C:\Users\tong_\HelloWorldRN\index.android.js  
C:\Users\tong_\HelloWorldRN\index.android.js:7  
import React, { Component } from 'react';  
^^^^^^  

SyntaxError: Unexpected token import  
    at createScript (vm.js:56:10)  
    at Object.runInThisContext (vm.js:97:10)  
    at Module._compile (module.js:542:28)  
    at Object.Module._extensions..js (module.js:579:10)  
    at Module.load (module.js:487:32)  
    at tryModuleLoad (module.js:446:12)  
    at Function.Module._load (module.js:438:3)  
    at Module.runMain (module.js:604:10)  
    at run (bootstrap_node.js:389:7)  
    at startup (bootstrap_node.js:149:9)  

Process finished with exit code 1  

## 分析
1、ES6不支持  
2、运行的是React Native项目，而不是单纯的js文件。所以应该配置运行工具  

## 解决办法
配置运行工具:  
win参考:
[WebStorm运行React Native项目](https://github.com/RamboTong/MobileDevelopment/blob/master/04React%20Native%E5%BC%80%E5%8F%91%E5%B7%A5%E5%85%B7WebStorm/WebStorm%E8%BF%90%E8%A1%8CReact%20Native%E9%A1%B9%E7%9B%AE.md)  

mac参考:[WebStorm里面配置运行React Native的方案 ](http://www.cnblogs.com/shaoting/p/6110202.html)
