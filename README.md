# MyPlugin
Cordova 插件

## 安装插件
1、安装:
在项目工程根目录下，在终端输入一下命令进行安装
```
cordova plugin add <本插件地地址>
```
## 使用
在需要显示alert的地方调用:
```
com.charls.MyPlugin.coolMethod('ccc', function success() {
        // 成功回调
    }, function failure() {
        // 失败回调
    });
```


