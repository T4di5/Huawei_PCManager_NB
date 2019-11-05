# Huawei_PCManager_NB

在华为电脑管家`PCManager`基础上做了一点修改，让`PCManager`支持在非华为系电脑运行，完美支持多屏协同功能。

# 使用方法

注意：华为原版PCManager仅支持Windows10 X64系统，电脑需有WIFI和蓝牙功能。

1. 安装`PCManager_Setup_10.0.2.59.exe`到`C:\Program Files\Huawei\PCManager`(默认路径)。
2. 打开`Windows`任务管理器-进程项，找到`MateBookService.exe`-`Huawei PCManger Widnows Service`，将其结束。
2. 复制`Util.dll`到`C:\Program Files\Huawei\PCManager`替换原始`Util.dll`。
3. 打开华为电脑管家，我的手机->立即连接->扫码连接，手机打开华为浏览器扫描确认连接。
4. 如果功能不正常（提示加载服务），需要重启一次电脑系统。

另：
电脑管家官网[下载地址](https://consumer-tkb.huawei.com/tkbapp/downloadWebsiteService?websiteId=1697397)

文件hash:

```
Huawei_PCManager_NB\PCManager_Setup_10.0.2.59.exe
MD5: 20AF7D3D82A9ACFA1ACDC82F45A34493
SHA1: F66F0A8E1F39C9165F5DFBF73D8BB9EBEF6750AD
Util.dll
MD5: 041AA7C4812BDD3CA17A8C238A818C6B
SHA1: 51A85CBCD079C8C2BFD4484F562632B1CCF3A535
```

若华为电脑管家版本更新，本项目会同步更新，具体请关注公众号：汉客儿。

交流群：[753894145](https://jq.qq.com/?_wv=1027&k=5ww6tlB)

**如果觉得作者给你提供了一点帮助，请他喝一杯咖啡吧**

![img](pay.png)