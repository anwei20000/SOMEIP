# SOME/IP 资料
---
**这里是自己学习和工作中整理的关于SOME/IP的资料，托管在这里，希望能帮助到需要的朋友，或者能进行讨论，共同学习，共同进步。**

## wireshark 协议解析插件
[vsomeip.lua](./src/vsomeip.lua)
是用于wireshark解析SOME/IP协议的lua插件，
在wireshark中使用该插件，需要开启wireshark的插件功能，并且在wireshark的安装目录下打开init.lua脚本，定位到最后一行，添加如下信息
```
dofile(DATA_DIR.."vsomeip.lua")
```

### 运行效果截图
 ![运行效果截图](./img/demo1.PNG)


 ## webapi
使用asp.net core 来定义SOMEIP相关的webapi,同时使用swagger自动生成接口文档，接口使用假设的系统，这里并不是真正意义上的webapi,只是在借用webapi的概念来实现适合自己的接口,旨在关心Model和Example Value两部分.
![运行效果截图](./img/webapi_swagger.PNG)

