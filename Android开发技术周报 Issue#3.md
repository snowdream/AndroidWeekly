# Android开发技术周报 Issue#3

## 业界新闻
#### 1. [Kotlin 1.1 Beta 发布，正式版还会远吗？](https://www.oschina.net/news/81163/kotlin-1-1-beta-release)
Kotlin 1.1 的最大更新是完全支持对 JavaScript 的编译，以及在 JVM, Android 和 JavaScript 上的协程（Coroutines）

## Android开发
#### 1. [Annotation-Processing-Tool详解](http://qiushao.net/2015/07/07/Annotation-Processing-Tool详解/)
在这篇文章中我将阐述如何实现一个注解处理器。首先我将向你解释什么是注解处理器，你可以使用这个强大的工具来做什么及不能做什么。接下来我们将一步一步来实现一个简单的注解处理器。

#### 2. [ android-apt 即将退出历史舞台](http://blog.csdn.net/asce1885/article/details/52878076)
伴随着 Android Gradle 插件 2.2 版本的发布，近期 android-apt 作者在官网发表声明证实了后续将不会继续维护 android-apt，并推荐大家使用 Android 官方插件提供的相同能力。也就是说，大约三年前推出的 android-apt 即将告别开发者，退出历史舞台，Android Gradle 插件提供了名为 annotationProcessor 的功能来完全代替 android-apt。

#### 3. [Android - 利用Eclipse Memory Analyzer(MAT)检测内存泄露问题](http://cashow.github.io/android-detect-out-of-memory-with-eclipse-memory-analyzer.html)
通过LeakCanary或者Eclipse Memory Analyzer（简称MAT），可以较方便地定位内存泄露的源头。

#### 4. [Android编译时注解框架系列](https://github.com/lizhaoxuan/Android-APT-Framework)
Android编译时注解框架系列博客。

#### 5. [谈谈Java接口与实现的分离以及隐藏实现](http://www.jianshu.com/p/ede85f9f60b7)
下面我将说说为什要进行接口和实现的分离、对实现方式进行隐藏 以及怎么实现它们.

#### 6. [看 AspectJ 在 Android 中的强势插入](http://t.cn/RMFLPVd)
AOP是Aspect Oriented Programming的缩写，即『面向切面编程』。

#### 7. [花式实现图片3D翻转效果](http://t.cn/RMFLYtr)
一个很炫的3D翻转切换图片的效果。

#### 8. [Espresso浅析和使用](http://t.cn/RMFLgPq)
Espresso是一个Google官方提供的Android应用UI自动化测试框架。

#### 9. [ExifInterface 支持库简介](http://t.cn/RMFyfBV)
随着 25.1.0 支持库的发布，支持库大家庭迎来了一名新成员：ExifInterface 支持库。由于 Android 7.1 引入了对框架 ExifInterface 的重大改进，因此只有通过支持库的 ExifInterface 让所有 API 9 以上的设备都能利用这些改进才有意义。

#### 10. [谈谈Android的so](http://allenfeng.com/2016/11/06/what-you-should-know-about-android-abi-and-so/)
一般情况下，我们不需要关心so。但是当APP使用的第三方SDK中包含了so文件，或者自己需要使用NDK开发某些功能，就有必要去好好了解下so的一些知识。早期的Android设备只支持ARMv5的CPU架构，随着Android系统的快速发展，搭载Android的硬件平台也早已多样化了，又加入了ARMv7，x86，MIPS，ARMv8，MIPS64和x86_64。

#### 11. [美团热更新方案 ASM 实践](http://geek.csdn.net/news/detail/133086)
从《Android热更新方案 Robust》一文可知，美团热更新使用的是 Instant Run 的方案。本文将着重于分享美团热更新方案中没讲到的部分，包含以下几个方面：1.作为云服务提供厂商，需要提供给客户 SDK，SDK 发布后同样要考虑 Bug 修复问题。此处将介绍作为 SDK 发布者的热更新方案选型，即为什么使用美团方案&Instant Run 方案。2.美团方案实现的大致结构；3.ASM 插桩的过程，字节码导读，以及遇到的各种坑


#### 12. [Android 5.0(Lollipop)中的SurfaceTexture，TextureView, SurfaceView和GLSurfaceView](http://blog.csdn.net/jinzhuojun/article/details/44062175)
SurfaceView从Android 1.0(API level 1)时就有 。它继承自类View，因此它本质上是一个View。但与普通View不同的是，它有自己的Surface。我们知道，一般的Activity包含的多个View会组成View hierachy的树形结构，只有最顶层的DecorView，也就是根结点视图，才是对WMS可见的。这个DecorView在WMS中有一个对应的WindowState。相应地，在SF中对应的Layer。而SurfaceView自带一个Surface，这个Surface在WMS中有自己对应的WindowState，在SF中也会有自己的Layer。

## 开源库&项目&工具
#### 1. [android-apt](https://bitbucket.org/hvisser/android-apt)
The android-apt plugin assists in working with annotation processors in combination with Android Studio. It has two purposes:
 *  Allow to configure a compile time only annotation processor as a dependency, not including the artifact in the final APK or library
 *  Set up the source paths so that code that is generated from the annotation processor is correctly picked up by Android Studio.

#### 2. [Big Bang](https://github.com/SmartisanTech/android)
什么是大爆炸（Big Bang）？

用拇指大面积按压屏幕中的文字，Big Bang 会将你按住的那一段文字全部“炸”开并且按照语义智能拆分成易于选取的独立的字和词，由你随心所欲地选择，并可直接搜索、分享和复制。Big Bang 开创性地解决了在手机这样的小屏幕上难于处理文字的弊端。

#### 3. [CodeView](https://github.com/tiagohm/CodeView)
Android Code Highlighter

#### 4. [SlantedTextView](https://github.com/HeZaiJin/SlantedTextView/blob/master/README-cn.md)
一个倾斜的TextView,适用于标签效果。

![SlantedTextView](https://github.com/HeZaiJin/SlantedTextView/raw/master/screen_shot/screenshot.png)

#### 5. [AnimatedRecordingView](https://github.com/HeZaiJin/AnimatedRecordingView)
Android animated recording view .

![AnimatedRecordingView](https://github.com/HeZaiJin/AnimatedRecordingView/raw/master/screen_shot/animated_recording.gif)

#### 6. [ARouter](https://github.com/alibaba/ARouter/blob/master/README_CN.md)
 Android平台中对页面、服务提供路由功能的中间件

#### 7. [zxing-android-embedded](https://github.com/journeyapps/zxing-android-embedded)
Port of the ZXing Android application as an Android library project, for embedding in an Android application.

## 联系方式
* Email：yanghui1986527#gmail.com
* QQ群: 529327615     
* 微信公众号:  sn0wdr1am    

![sn0wdr1am](https://static.dingtalk.com/media/lADOmAwFCs0BAs0BAg_258_258.jpg)
