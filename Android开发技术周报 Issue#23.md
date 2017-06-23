# Android开发技术周报 Issue#23

    声明：所有内容收集整理自网络。如有侵权，请联系删除。微信公众号上请点击“阅读原文”阅读完整版本。
    
## 业界新闻
#### 1. [增加新的 Brotli 压缩算法](http://t.cn/RoIfzxb)
最近，我们宣布为 Google AMP Cache 增加新的 Brotli 压缩算法。现在，通过 Google AMP Cache 缓存的所有 AMP 文档均可通过 Brotli 进行压缩，这将为我们的用户节省大量带宽，有助于推动实现我们改善移动体验的目标。

#### 2. [又一第三方 ROM 死亡，Tencent OS 6月28日停止服务](https://www.oschina.net/news/86078/tencent-os-be-discontinued-on-june-28th)
据 TechWeb 报道，昨日晚间腾讯管理员在论坛宣布 Tencent OS 将在 6 月 28 日停止服务，并表示请用户尽快保存数据信息。对于停服原因，腾讯 Tencent OS 称是因为第三方 ROM 市场萎缩。

#### 3. [Blockly 1.0 正式版发布，Google 可视化编程工具](https://www.oschina.net/news/86016/blockly-1-0)
Blockly 是 Google 开源的一个基于 Web 的可视化编辑器，只需要拖动几个图形就可以编程。Blockly 1.0 主要面向 Android 和 iOS 移动端。

## Android开发
#### 1. [Android 混淆那些事儿](http://t.cn/RoIfkxC)
本文主要讲述了代码混淆和资源混淆的原理，Studio默认的混淆方案，混淆的参数，以及如何对Apk进行代码混淆(自定义混淆文件)和资源混淆(结合微信混淆和美团混淆两种方案)，避免Apk被逆向。

#### 2. [reCAPTCHA Android API 简介](http://t.cn/RoIfqzn)
十年前，我们发布了 reCAPTCHA，那时，我们设定了一个简单的目标：让用户能够放心地访问他们喜爱的网站，而不必担心垃圾邮件和滥用行为。十年来，reCAPTCHA 发生了不小的改变。它从针对街道号码和名称的变形文本发展到 2014 年的无人机识别系统 reCAPTCHA，再到今年 3 月份的不可见 Invisible reCAPTCHA。

![reCAPTCHA Android API 简介](http://bp.googleblog.cn/-8XZF7G6MPgw/WTmj2gekLxI/AAAAAAAABJY/WBN6YTzZ7B0ohNIzPIdmd84mUie_ZXppgCLcB/s1600/image2.gif)

#### 3. [GET 和 POST 有什么区别？及为什么网上多数答案都是错的](http://t.cn/RoIIDL0)
如果有人问你，GET和POST，有什么区别？你会如何回答？

#### 4. [Android热修复升级探索（三）](http://t.cn/RoIMmQD)
对于Android下的冷启动类加载修复，最早的实现方案是QQ空间提出的dex插入方案。该方案的主要思想，就是把插入新dex插入到ClassLoader索引路径的最前面。这样在load一个class时，就会优先找到补丁中的。后来微信的Tinker和手Q的QFix都基于该方案做了改进，而这类插入dex的方案，都会遇到一个主要的问题，就是如何解决Dalvik虚拟机下类的pre-verify问题。

#### 5. [Android增量代码测试覆盖率工具](http://t.cn/RoIxCpi)
美团点评业务快速发展，新项目新业务不断出现，在项目开发和测试人员不足、开发同学粗心的情况下，难免会出现少测漏测的情况，如何保证新增代码有足够的测试覆盖率是我们需要思考的问题。

#### 6. [Java线程通信（Thread Signaling）](http://www.jianshu.com/p/5b9fdae43335)
线程通信的目的就是让线程间具有互相发送信号通信的能力。
而且，线程通信可以实现，一个线程可以等待来自其他线程的信号。举个例子，一个线程B可能正在等待来自线程A的信号，这个信号告诉线程B数据已经处理好了。

#### 7. [Android 之 Shader 用法详细介绍](http://www.jianshu.com/p/83af13b41bb6)
Shader 是Android中非常重要的一个类 一般称之为着色器,其作用是用来给图像着色，我们一般在自定义View的时候通过paint.setShader(Shader shader)使用比较多 Shader有五个子类 下面将对每个API的使用做详细介绍

## 专题栏目 － HotFix
#### 1. [HotFix原理介绍及使用总结](http://www.jianshu.com/p/6f0ae1e364d9)
以补丁的方式动态修复紧急Bug，不再需要重新发布App，不再需要用户重新下载，覆盖安装(来自：安卓App热补丁动态修复技术介绍)

#### 2. [Tinker -- 微信Android热补丁方案](https://github.com/Tencent/tinker/wiki)
Tinker是微信官方的Android热补丁解决方案，它支持动态下发代码、So库以及资源，让应用能够在不需要重新安装的情况下实现更新。当然，你也可以使用Tinker来更新你的插件。

#### 3. [Alibaba-AndFix Bug热修复框架原理及源码解析](http://blog.csdn.net/qxs965266509/article/details/49816007)
AndFix的原理就是方法的替换，把有bug的方法替换成补丁文件中的方法。 

#### 4. [Amigo](https://github.com/eleme/Amigo/wiki)
Amigo 原理与 QQZone 的方案有些类似，QQZone,Tinker,Nuwa这类方案是通过修改PathClassLoader中的dex实现的，Amigo则是釜底抽薪直接替换ClassLoader。

#### 5. [安卓App热补丁动态修复技术介绍](http://t.cn/RGNTNKm)
当一个App发布之后，突然发现了一个严重bug需要进行紧急修复，这时候公司各方就会忙得焦头烂额：重新打包App、测试、向各个应用市场和渠道换包、提示用户升级、用户下载、覆盖安装。有时候仅仅是为了修改了一行代码，也要付出巨大的成本进行换包和重新发布。

#### 6. [QFix探索之路——手Q热补丁轻量级方案](http://t.cn/RoIr3jK)
QFix 是手Q团队近期推出的一种新的 Android 热补丁方案，在不影响 app 运行时性能（无需插桩去 preverify）的前提下有效地规避了 dalvik 下”unexpected DEX”的异常，而且还是很轻量级的实现：只需调用一个很简单的方法就能办到。

#### 7. [阿里震撼业界—推出首个非侵入式热修复方案Sophix，颠覆移动端传统发版更新流程！](http://t.cn/RoId5mP)
2017年6月11日，手淘技术团队联合阿里云正式发布了史上首个非侵入式移动热更新解决方案——Sophix。

## 开源库&项目&工具
#### 1. [【干货】github上十二款最著名的Android播放器开源项目](http://t.cn/RoIMqtY)
Ijkplayer 是Bilibili发布的基于 FFplay 的轻量级 Android/iOS 视频播放器。实现了跨平台功能，API 易于集成；编译配置可裁剪，方便控制安装包大小；支持硬件加速解码，更加省电；提供 Android 平台下应用弹幕集成的解决方案。

#### 2. [2017 上半年最酷，最受欢迎的30 个 Android 库](http://t.cn/RoIx5t6)
我从 《The 30 Coolest Android Libraries from Spring 2017》这篇文章中的 30 个最酷的 Android 库挑了几个我感觉比较好玩的几个 Android 库分享给大家。如果想看完整的 30 个库，可以点击“阅读原文”查看。

#### 3. [blockly-android](https://github.com/google/blockly-android)
Blockly for Android

#### 4. [LICEcap](http://www.cockos.com/licecap/)
simple animated screen captures

## 联系方式
* Email：yanghui1986527#gmail.com
* Github: https://github.com/snowdream
* Blog: http://snowdream.github.io/blog/
* 简书：http://www.jianshu.com/u/748f0f7e6432
* 云栖博客：https://yq.aliyun.com/u/snowdream86 
* QQ群: 529327615     
* 微信公众号:  sn0wdr1am    

![sn0wdr1am](https://static.dingtalk.com/media/lADOmAwFCs0BAs0BAg_258_258.jpg)
