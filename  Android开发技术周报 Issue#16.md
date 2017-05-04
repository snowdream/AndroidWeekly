# Android开发技术周报 Issue#16

    声明：所有内容收集整理自网络。如有侵权，请联系删除。微信公众号上请点击“阅读原文”阅读完整版本。
    
## 业界新闻
#### 1. [今年Android全球手机市场份额将增长5个百分点至90%](http://www.cnbeta.com/articles/tech/606287.htm)
业界人士估计，今年Android在全球智能手机市场上的份额由去年的85%增长至90%。

#### 2. [Glide 3.8.0 发布，Android 图片加载和缓存库](https://www.oschina.net/news/84433/glide-3-8-0)
更新内容如下：

### 新特性

给 GIF 新增 getTotalLoopCount (#1836, thanks to @toyama-sumio)

添加方法以关闭不使用集成库的应用程序的清单解析(#1754, thanks to @joshzana)

添加 Uris 连接支持(#394, thanks to  @R4md4c)

更好地处理 OOMs (#1057, thanks to @dmapr and @ihenchi)

### 修复

修复了 GIF 处理和解码的各种问题 (thanks @TWiStErRob, @toyama-sumio, @osama and @kojilin)


## Android开发
#### 1. [关于 Android 7.0 适配中 FileProvider 部分的总结](http://t.cn/RaZehY3)
由于 Android 7.0 或更高版本的系统在国内手机市场上的占比不是很高，很多 Android 开发人员并没有做 7.0 适配工作，同时测试人员也容易忽视这方面的兼容问题。这导致 7.0 及以上版本的手机用户在使用到应用部分功能时可能出现 App 崩溃闪退。其中，大部分原因都是由项目中使用到 file:// 类型的 URI 所引发的。本文我们便来一探究竟。

#### 2. [写给Android开发者的Java 8简单入门教程](http://tangpj.com/2017/04/24/java8-inAndroid/)
Java 8是在2014年3月发布的，Android工程师为什么要关心Java 8呢？理由是Java 8所做的改变比Java历史上任何一次改变都要深远。Java 8对于程序员的主要好处在于它提供了更多的编程工具和概念，能以更快，更重要的是能以更为简洁、更易于维护的方式解决新的或现有的编程问题。我希望通过这篇文章，能让读者对Java 8产生兴趣，从而使用Java 8进行开发。

#### 3. [有赞App模块化实战经验总结](https://youzanmobile.github.io/2017/04/14/youzan-app-modularization/)
随着有赞电商业务的不断发展壮大，App端所承担的功能也越来越重，特别是代码几易其主之后开始变得杂乱无章，牵一发而动全局的事情时常发生。为了应对团队壮大之后的开发模式，我们必须要对业务进行隔离，同时沉淀出通用组件，完善移动开发的基础设施。

#### 4. [Android中的FORTIFY](http://developers.googleblog.cn/2017/04/android-fortify.html)
FORTIFY是Android自2012年中以来一直配备的一项重要的安全功能。去年初，在将默认的C/C++编译器从GCC迁移为Clang后，Google投入大量时间和精力，确保FORTIFY在Clang中的质量与之前相当。为做到这一点，Google重新设计了某些关键的FORTIFY功能的工作方式，具体将在下文介绍。


#### 5. [分析Android V2新签名打包机制](http://t.cn/RaZDz70)
Android Studio 2.2发布之后公示了很多新特性，其中一些特性继承在了gradle plugin当中，这些不易被我们发现,比如新的签名机制(APK Signature Scheme v2)，本文对Android Gradle 2.2新推出来的新签名打包机制(V2新签名方案)作出相关分析，目前在Android 7.0以及之上版本已经对这套新签名机制提供了支持，因此随着版本的提升，新签名机制方案将是大势所趋。


#### 6. [Android 方法数杂谈](http://t.cn/RaZDSwD)
在做Android应用研发时，尤其是开发大型应用时，我们很容易遇到Android方法超过65536的现象。即便进行分 dex 处理，在功能日益增加的今天，主 dex 依然会面临方法数不够用的窘境，然后不得不通过各种压缩、裁剪代码，才得以上线。虽然现在已有广为人知的现成解决方案，然墨子有云："治于神者，众人不知其功，争于明者，众人知之"，回想起这几年间 Android 程序员和方法数之间林林总总的相爱相杀，发现很多问题既没有事前疏导，也缺乏事后防范总结，所以此刻谈谈方法数这个问题的本源，对达到“治于神”这一境界是存在其必要性的。

#### 7. [Android之低功耗蓝牙的基本使用](http://t.cn/RaZDjjs)
最近在工作中使用到蓝牙的功能，当然我们这个蓝牙时跟蓝牙芯片结合使用的，而不是手机跟手机连接通信的。其实本质时差不多的，只是设备不一样罢了。在这里我不会贴出蓝牙那些协议等等复杂的名词解释，因为这个不是一两句话能解释的清楚，在我们先不太了解蓝牙的这些专业名词之前，我们先掌握它的基本使用就可以了，后续如果想深入了解的话，我们再花时间去学习。本文介绍的低功耗的蓝牙，是 Android 4.3 才开始支持的，而要使用传统蓝牙和高版本的蓝牙请参照官方文档，有中文介绍哦。

#### 8. [Android WebView详解，常见漏洞详解和安全源码](http://t.cn/RaZDR0k)
现在市面上的 APP 根据类型大致可以分为 3 类：Native APP、Web APP 和 Hybrid APP，而 Hybrid APP 兼具 “Native APP 良好用户交互体验的优势”和 “Web APP 跨平台开发的优势”，现在很多的主流应用也是使用 Hybrid 模式开发的。

#### 9. [Android自定义全键盘](http://www.jianshu.com/p/325a7efd5d0d)
制作一个自定义全键盘

![Android自定义全键盘](http://upload-images.jianshu.io/upload_images/3866329-b3db6646a9484aaa.gif?imageMogr2/auto-orient/strip)

## 开源库&项目&工具
#### 1. [litho](http://fblitho.com)
A declarative framework for building efficient UIs on Android. http://fblitho.com

#### 2. [litho-picasso](https://github.com/charbgr/litho-picasso)
Picasso image-loading Component for Litho

#### 3. [AwesomeQRCode](https://github.com/SumiMakito/AwesomeQRCode)
一个优雅的(不起眼的) QR 二维码生成器

![AwesomeQRCode](https://raw.githubusercontent.com/SumiMakito/AwesomeQRCode/master/art/awesome-qr-1.png)

#### 4. [MeiTuan](https://github.com/huanxsd/MeiTuan)
高仿美团客户端React-Native版，支持iOS、Android。

## 联系方式
* Email：yanghui1986527#gmail.com
* Github: https://github.com/snowdream
* Blog: http://snowdream.github.io/blog/
* 简书：http://www.jianshu.com/u/748f0f7e6432
* 云栖博客：https://yq.aliyun.com/u/snowdream86 
* QQ群: 529327615     
* 微信公众号:  sn0wdr1am    

![sn0wdr1am](https://static.dingtalk.com/media/lADOmAwFCs0BAs0BAg_258_258.jpg)
