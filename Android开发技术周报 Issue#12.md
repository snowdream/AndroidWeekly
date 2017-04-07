# Android开发技术周报 Issue#12

    声明：所有内容收集整理自网络。如有侵权，请联系删除。微信公众号上请点击“阅读原文”阅读完整版本。
    
## 业界新闻
#### 1. [Android Studio 2.4 Preview 4 发布，内置 Java 8 支持](https://www.oschina.net/news/83556/android-studio-2-4-preview4)
Android Studio 2.4 Preview 4 发布了。Android Studio 2.4 的最新预览版包括构建工具和模拟器中的 Google Play 的更新，以及一些错误修复。

#### 2. [Android 超越 Windows 成市场份额第一操作系统](https://www.oschina.net/news/83517/android-market-share-higher-than-windows)
互联网分析公司 Statcounter 发布报告称，随着移动设备的快速普及，Android 如今首次超越 Windows，成为消费者接入互联网使用最广泛的操作系统。

#### 3. [Google I/O 2017 大会时间表出炉：安卓 8.0 时代来临](https://www.oschina.net/news/83444/google-io-2017-conference-schedule)
虽然距离谷歌 I/O 2017 大会开幕还有一个多月的时间，但谷歌在今天已经悄悄放出大会时间表，首场会议将在美国时间 5 月 17 日上午十点在加州举办，所有会议议程将在谷歌 I/O 官网上公布。

#### 4. [恶意 Wi-Fi 网络能劫持 Android 设备](https://www.oschina.net/news/83613/android-phones-vulnerable-to-device-hijacks-over-wi-fi)
Broadcom Wi-Fi 芯片被 发现存在漏洞，允许恶意 Wi-Fi 信号在设备上执行任意代码。

该漏洞影响 iOS 和 Android 设备，苹果已经 释出了补丁，Google 也已经 释出了补丁，但众所周知 Android 设备的安全更新相比苹果是完全不同的故事。

## Android开发
#### 1. [Android消息机制源码分析](http://t.cn/R63EtYN)
从源码的角度分析了Handler机制

#### 2. [Glide 源码详解](http://t.cn/R63ECzJ)
我们一起来研究一下Glide的源码,看看Glide到底是怎么将一张图片加载出来的。

#### 3. [从Android代码中来记忆23种设计模式](http://www.jianshu.com/p/1a9f571ad7c0)
从Android代码中来记忆23种设计模式

#### 4. [经典随机Crash之一：线程安全](https://mp.weixin.qq.com/s/GHGMHW0Mz7eYVh7EaF6VNw)
Android QQ 在2016下半年连着好几个版本二灰 Crash 率都很高，如果说有新需求，一灰的 Crash 率高，还能找点理由，可是开发童鞋解过一灰的 Crash 单后，为啥二灰还有这么高的 Crash 率，我们还有覆盖全 SNG、不少外 BG 明星产品的终端稳定性测试工具 NewMonkey 随身版每天都在跑，更何况大多 Top Crash 都发生在用户使用很普通、很频繁的场景，实在令人匪夷所思，那段时间抄送各老板的运营邮件 Crash 率数据天天标红，项目组人心惶惶，发个版本感觉要烧高香，当时作为 Android NewMonkey 核心成员的我更是压力山大，在这样的背景下，我临危受命，负责研究外网 Top Crash，尽可能找到一些共性问题

#### 5. [经典随机Crash之二：Android消息机制](http://t.cn/R6r54g9)
好几次灰度top1、top2 Crash发生场景：在很平常、频繁的使用页面，打开一个界面，马上返回，piaji，挂了，估计用户心中有千万只草泥马在奔腾，手机QQ究竟怎么呢？

#### 6. [Android减包 － 减少APK大小](https://mp.weixin.qq.com/s/ox4WFLMZG63wuoD6_-rCyQ)
用户经常会避免下载看起来体积较大的应用，特别是在不稳定的2G、3G网络或者在以字节付费的网络。这篇文章描述了怎样减少你的APK大小，这会让更多的用户愿意下载你的应用。

#### 7. [Android减包 - 使用APK Analyzer分析你的APK](http://mp.weixin.qq.com/s/jj727RQGmPooKaJwPyVUlA)
Android Studio 2.2包含了APK Analyzer，通过它我们能够直观地看到APK的组成。使用APK Analyzer不仅能够减少你花在debug上的时间，而且还能减少你的APK大小。使用APK Analyzer，你能够实现：1.查看APK中文件的绝对大小和相对大小。（译注：相对大小指的是该文件占整个APK大小的百分比）；2.理解DEX文件的组成。（译注：能看到DEX文件中包含了哪些类）；3.快速查看APK中文件的最终版本（比如AndroidManifest.xml）。

#### 8. [一看你就懂，超详细java中的ClassLoader详解](http://blog.csdn.net/briblue/article/details/54973413)
ClassLoader翻译过来就是类加载器，普通的Java开发者其实用到的不多，但对于某些框架开发者来说却非常常见。理解ClassLoader的加载机制，也有利于我们编写出更高效的代码。ClassLoader的具体作用就是将class文件加载到jvm虚拟机中去，程序就可以正确运行了。但是，jvm启动的时候，并不会一次性加载所有的class文件，而是根据需要去动态加载。想想也是的，一次性加载那么多jar包那么多class，那内存不崩溃。本文的目的也是学习ClassLoader这种加载机制。

#### 9. [Android Shader 实战 各种炫酷效果的基石](http://t.cn/R6rqNoE)
介绍Android Shader的各种用法。

## 开源库&项目&工具
#### 1. [Android-Marshmallow-Boot-Animation](https://github.com/Cleveroad/Android-Marshmallow-Boot-Animation)
Android Marshmallow 系统启动动画效果

#### 2. [FireworkyPullToRefresh](https://github.com/Cleveroad/FireworkyPullToRefresh)
一个炫酷的下拉刷新效果

#### 3. [ShadowImageView](https://github.com/yingLanNull/ShadowImageView)
一个可以根据图片变颜色，更加细腻的阴影效果的 Imgae 控件

## 联系方式
* Email：yanghui1986527#gmail.com
* Github: https://github.com/snowdream
* Blog: http://snowdream.github.io/blog/
* 简书：http://www.jianshu.com/u/748f0f7e6432
* 云栖博客：https://yq.aliyun.com/u/snowdream86 
* QQ群: 529327615     
* 微信公众号:  sn0wdr1am    

![sn0wdr1am](https://static.dingtalk.com/media/lADOmAwFCs0BAs0BAg_258_258.jpg)
