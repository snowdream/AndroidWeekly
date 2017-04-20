# Android开发技术周报 Issue#14

    声明：所有内容收集整理自网络。如有侵权，请联系删除。微信公众号上请点击“阅读原文”阅读完整版本。
    
## 业界新闻
#### 1. [Android Studio 2.4 Preview 6 发布](https://www.oschina.net/news/83949/android-studio-2-4-preview-6)
Android Studio 2.4 Preview 6 于2017年4月13号发布了。Beta版本发布前还将发布Preview 7版本。

## Android开发
#### 1. [Android O 中对设备标识符所做的变更](http://t.cn/RXXRMCL)
Android O 引入若干改进，帮助用户控制标识符的使用。这些改进包括：
* 限制使用不可重置的设备范围标识符
* 更新 Android O WLAN 堆栈，更改 Pixel、Pixel XL 和 Nexus 5x 手机所使用的 WLAN 芯片组固件，以便在探测请求中随机分配 MAC 地址
* 更新应用请求帐号信息的方式，提供更多面向用户的控制

#### 2. [用两张图告诉你，为什么你的App会卡顿?](http://t.cn/RXXEwSv)
从这篇文章中你能获得这些料：
* 知道setContentView()之后发生了什么？
* 知道Android究竟是如何在屏幕上显示我们期望的画面的？
* 对Android的视图架构有整体把握。
* 学会从根源处分析画面卡顿的原因。
* 掌握如何编写一个流畅的App的技巧。
* 从源码中学习Android的细想。
* 收获两张自制图，帮助你理解Android的视图架构。

#### 3. [Android编译时，怎么自动生成代码？](http://www.jianshu.com/p/96ce81e68445)
今天的主要内容是，在IDE编译时，怎么去动态生成Java和class文件。

#### 4. [从未如此惊艳！你好，SuperTextView](http://www.jianshu.com/p/1b91e11e441d)
欢迎使用SuperTextView，这篇文档将会向你展示如何使用这个控件来提高你构建项目的效率。

![SuperTextView](http://upload-images.jianshu.io/upload_images/1869462-ad8839d482446393.gif?imageMogr2/auto-orient/strip)

#### 5. [Android ConstraintLayout使用指南](http://blog.coderclock.com/2017/04/09/android/android-constraintlayout/)
ConstraintLayout翻译成中文也称为约束布局，类似于iOS中的布局约束。升级到Android Studio 2.3之后，IDE默认生成的Activity布局都是以ConstraintLayout做为根布局，作者体验了一把这个Google去年就开始力推的ConstraintLayout后，觉得非常不错，本文主要是记录ConstraintLayout各个方面的使用知识。

#### 6. [Android插件化Hook技术之---Activity的启动过程拦截](http://t.cn/RXXRp2Q)
这篇文章主要讲解如何利用动态代理技术Hook掉系统的AMS服务，来实现拦截Activity的启动流程。代码量不是很多，为了更容易的理解，需要掌握JAVA的反射，动态代理技术，以及Activity的启动流程。

## 开源库&项目&工具
#### 1. [TranslationPlugin V1.3.4 发布，JetBrains IDE/Android Studio插件](http://yiiguxing.github.io/TranslationPlugin/)
JetBrains IDE/Android Studio 翻译插件 TranslationPlugin V1.3.4 发布了。更新内容：

* 支持自定义字体，再也不怕小方块了

* 使用公共API KEY时警告

* "频繁请求"和"API KEY错误"提示添加跳转至设置页链接以方便设置API KEY

* 优化历史记录

* Bug修复

![TranslationPlugin](https://github.com/YiiGuxing/TranslationPlugin/raw/master/images/screenshots.gif)

#### 2. [gifencoder](https://github.com/square/gifencoder)
A pure Java library implementing the GIF89a specification. Suitable for use on Android.

## 联系方式
* Email：yanghui1986527#gmail.com
* Github: https://github.com/snowdream
* Blog: http://snowdream.github.io/blog/
* 简书：http://www.jianshu.com/u/748f0f7e6432
* 云栖博客：https://yq.aliyun.com/u/snowdream86 
* QQ群: 529327615     
* 微信公众号:  sn0wdr1am    

![sn0wdr1am](https://static.dingtalk.com/media/lADOmAwFCs0BAs0BAg_258_258.jpg)
