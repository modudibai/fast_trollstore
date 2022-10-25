# fast_trollstore介绍

Trollstore是一个非常牛B的工具，可以让非越狱的iOS设备（14-15.4.1）非常方便的安装各种ipa软件，而且是永久的。
Trollstore项目地址：https://github.com/opa334/TrollStore/

本项目的作用是，让在国内朋友在安装trollstore的时候，不再因为资源在github被墙，而安装失败或非常慢的问题，也就是一个trollstore在国内快速安装的梯子：）

本项目跟原项目 release-1.2.2 的功能完全一致，修改的内容如下：
* 辅助安装的TrollHelper.ipa 使用一个只有6M的《计算器+》应用替代官方40M+的《GTA Car Tracker》，提高下载和安装速度，功能没任何区别；
* 里面涉及到的 TrollStore.tar 和 ldid 下载地址都使用国内的proxy进行了代理和加速，安装不再报错；


# 安装

* iOS14：复制下面地址，在手机Safari浏览器地址栏里粘贴并前往，按照提示安装即可：
```
itms-services://?action=download-manifest&amp;url=https://cdn.jsdelivr.net/gh/modudibai/fast_trollstore@main/plist/trollstore-ios14.plist
```

* iOS15：复制下面地址，在手机Safari浏览器地址栏里粘贴并前往，按照提示安装即可：
```
itms-services://?action=download-manifest&amp;url=https://cdn.jsdelivr.net/gh/modudibai/fast_trollstore@main/plist/trollstore-ios15.plist
```

其他后续的安装步骤参照官方or往上其他教程即可，不再赘述。
