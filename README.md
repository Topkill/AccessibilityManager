# 无障碍管理器
本`APP`可以彻底取代系统设置里的无障碍设置页面。仅需要授权本`APP`写入安全设置即可使用。支持无障碍保活，不耗电不主动唤醒，且保活速度极快。

源码下载下来编译需要使用`Android Studio`，若不想使用`Android Studio`，也可使用命令行编译。

命令行编辑的前提是已经安装了`Android SDK`，

然后创建一个`local.properties`属性文件，里面添加`sdk.dir=你的android sdk路径`，

之后命令行输入`gradlew.bat assembleDebug`即可，这样生成的`apk`文件使用的`debug`签名。

你也可以输入对应的命令使用自己的私有签名。
