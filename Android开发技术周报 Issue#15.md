# Android开发技术周报 Issue#15

    声明：所有内容收集整理自网络。如有侵权，请联系删除。微信公众号上请点击“阅读原文”阅读完整版本。
    
## 业界新闻
#### 1. [Android Studio 2.4 Preview 6发布，支持Java 8语言功能](http://t.cn/RXERa23)
几天前，我们发布了 Android Studio 2.4 Preview 6。现在，在 javac/dx 编译路径中，Java 8 语言功能将得到 Android 构建系统的支持。Android Studio 的 Gradle 插件现在对 Java 8 类文件进行“脱糖”处理，仅保留与 Java 7 兼容的类文件，因此，您可以使用 Java 8 的 lambda、方法引用及其他功能。


#### 2. [Kotlin 1.1.2 发布，基于 JVM 的编程语言](https://www.oschina.net/news/84206/kotlin-1-1-2-is-out)
Kotlin 1.1.2 发布了，这是 Kotlin 1.1 系列的第二次 bug 修复和工具更新。

这次更新带来了编译器和 IntelliJ IDEA 插件的性能改进、工具的一些新功能以及所有领域中的错误修复。Kotlin 1.1.2 还带来了与 2.4.0-alpha 版本 Android Gradle 插件的兼容性。

此版本的完整更改列表可以在更新日志中找到。

更新内容较多，详情请参阅 发布主页。

Kotlin 是一个基于 JVM 的新的编程语言，由 JetBrains 开发。

其主要设计目标：

* 创建一种兼容 Java 的语言

* 让它比 Java 更安全，能够静态检测常见的陷阱。如：引用空指针

*  让它比 Java 更简洁，通过支持 variable type inference，higher-order functions (closures)，extension functions，mixins and first-class delegation 等实现。

* 让它比最成熟的竞争对手 Scala 语言更加简单。

#### 3. [2017年2月全球移动操作系统份额：国内安卓暴涨至86.4%](http://www.ithome.com/html/iphone/304298.htm)
Kantar Worldpanel放出了截止2017年2月底最新的全球移动操作系统份额数据，我们可以了解到三大移动操作系统在全球各地的具体份额情况。iOS系统在中国的份额降至了自2014年7月份以来的历史最低点，从去年同期的22.1%降至13.2%。而安卓系统则迎来增长，从原来的77.1%市占率飙升至86.4%


## Android开发
#### 1. [微信 SQLite 数据库修复实践](http://t.cn/RXEE8MQ)
众所周知，微信在后台服务器不保存聊天记录，微信在移动客户端所有的聊天记录都存储在一个 SQLite 数据库中，一旦这个数据库损坏，将会丢失用户多年的聊天记录。而我们监控到现网的损坏率是0.02%，也就是每 1w 个用户就有 2 个会遇到数据库损坏。考虑到微信这么庞大的用户基数，这个损坏率就很严重了。更严重的是我们用的官方修复算法，修复成功率只有 30%。损坏率高，修复率低，这两个问题都需要我们着手解决。

#### 2. [Android 插件技术实战总结](http://t.cn/RXEnzqU)
安卓应用开发的大量难题，其实最后都需要插件技术去解决。

现今插件技术的使用非常普遍，比如微信、QQ、淘宝、天猫、空间、携程、大众点评、手机管家等等这些大家在熟悉不过的应用都在使用。

插件技术可以给项目开发带来巨大的好处，比如：并行高效开发、模块解耦、解除单个dex函数不能超过65535的限制、动态更新升级、按需加载等等。

#### 3. [Android 减包 － 减少APK大小](http://t.cn/RXnIg2j)
用户经常会避免下载看起来体积较大的应用，特别是在不稳定的2G、3G网络或者在以字节付费的网络。这篇文章描述了怎样减少你的APK大小，这会让更多的用户愿意下载你的应用。

#### 4. [Android 新一代多渠道打包神器](http://t.cn/RXnMw5M)
ApkChannelPackage是一种快速多渠道打包工具，同时支持基于V1和V2签名进行渠道打包。插件本身会自动检测Apk使用的签名方法，并选择合适的多渠道打包方式，对使用者来说完全透明。

#### 5. [FileProvider 在 Android N 上的应用](https://zhuanlan.zhihu.com/p/26139355)
Android 从 N 开始不允许以 file:// 的方式通过 Intent 在两个 App 之间分享文件，取而代之的是通过 FileProvider 生成 content://Uri 。如果在 Android N 以上的版本继续使用 file:// 的方式分享文件，则系统会直接抛出异常，导致 App 出现 Crash，当然如果工程的 targetSDK 小于24，暂时还不会遇到这个问题，一旦升级到24及以上，则会立即出现上述问题，所以提早做好预防很有必要，否则等到线上曝出大量的 bug 就很被动了。

#### 6. [RemoteViews详细解释](http://www.haotianyi.win/2017/04/07/view/RemoteViews详细解释/)
RemoteViews表示的是一个view结构，它可以在其他进程中显示。由于它在其他进程中显示，为了能够更新它的界面，RemoteViews提供了一组基础的操作用于跨进程更新它的界面。RemoteViews主要用于通知栏通知和桌面小部件的开发，通知栏通知是通过NotificationManager的notify方法来实现的；桌面小部件是通过AppWidgetProvider来实现的，它本质上是一个广播(BroadcastReceiver)。这两者的界面都是运行在SystemServer进程中（跨进程）。本文详细介绍了RemoteViews的工作原理。

#### 7. [有效减少Android应用的方法数](https://zhuanlan.zhihu.com/p/26272085)
65k限制确实是个令人不爽的事情，本文会让你知道是哪些库用了大量的方法，并该怎么减少这些库的方法数。现在的应用越来越大，方法数经常达到65k限制。本文主要介绍了如何可视化library方法数和减少方法数的方法。

#### 8. [Android GC原理探究](https://mp.weixin.qq.com/s/CUU3Ml394H_fkabhNNX32Q)
想写一篇关于Android GC的想法来源于追查一个魅族手机图片滑动卡顿问题，由于不断的GC导致的丢帧卡顿的问题让我们想了很多方案去解决，所以就打算详细的看看内存分配和GC的原理，为什么会不断的GC，GC ALLOC和GC COCURRENT有什么区别，能不能想办法扩大堆内存减少GC的频次等等。

#### 9. [Android OOM案例分析](http://tech.meituan.com/oom_analysis.html)
在Android（Java）开发中，基本都会遇到java.lang.OutOfMemoryError（本文简称OOM），这种错误解决起来相对于一般的Exception或者Error都要难一些，主要是由于错误产生的root cause不是很显而易见。由于没有办法能够直接拿到用户的内存dump文件，如果错误发生在线上的版本，分析起来就会更加困难。本文从一个具体的案例切入，介绍OOM分析的思路及相关工具的使用。

#### 10. [Android无埋点数据收集SDK关键技术](http://www.jianshu.com/p/b5ffe845fe2d)
鉴于日益强烈的精细化运营需求，网易乐得从去年开始构建大数据平台，无埋点数据收集SDK因此立项，用于向大数据平台提供全量，完整，准确的客户端数据。无埋点数据收集SDK Android端从着手，到经历重构，逐步完善到现在已经有快一年的时间了。期间从开源社区以及同行中得到了一些很有意义的技术参考，因此在这个SDK趋于完善的今天，我们也考虑将这一路在技术上的探索经历和收获分享出来。

#### 11. [Android辅助功能(一)-AccessibilityEvent的分发](https://darkness463.github.io/2017/04/17/accessibility-event/)
目前关于辅助功能的使用的文章很多，但鲜有分析其具体实现的，本文基于Andoird 7.1.0_r7源码分析一下辅助事件是怎么分发的，只涉及事件的分发和辅助App的接收，之后有机会再讲一讲获取AccessibilityNodeInfo、进行操作等等的源码流程。

## 开源库&项目&工具
#### 1. [Matisse 图片选择器](https://github.com/zhihu/Matisse)
知乎APP开源的一个图片选择器，并内置了两套主题，UI设计基本满足大部分APP需求。

## 联系方式
* Email：yanghui1986527#gmail.com
* Github: https://github.com/snowdream
* Blog: http://snowdream.github.io/blog/
* 简书：http://www.jianshu.com/u/748f0f7e6432
* 云栖博客：https://yq.aliyun.com/u/snowdream86 
* QQ群: 529327615     
* 微信公众号:  sn0wdr1am    

![sn0wdr1am](https://static.dingtalk.com/media/lADOmAwFCs0BAs0BAg_258_258.jpg)
