# Android开发技术周报 Issue#21

    声明：所有内容收集整理自网络。如有侵权，请联系删除。微信公众号上请点击“阅读原文”阅读完整版本。
    
## 业界新闻

#### 1. [GMTC 2017 即将来袭！完整日程公布](http://t.cn/RSjeBCf)
再过一天，第二届 GMTC 全球移动技术大会就即将开始了，本届内容更加丰富，横跨移动开发、前端开发、大前端、AR/VR、移动 AI 多个主题，关注前沿技术和一线实践，给参会者送上精彩的大餐。

#### 2. [17 位谷歌 Android 开发专家是如何看待 Kotlin 的？](https://www.oschina.net/news/85468/what-do-17-google-developers-experts-for-kotlin)
我联系了一些这样的 Android 专家，我得到了来自 17 位的答复。我只是要求他们告诉我们关于 Kotlin 的一点想法，答案显然是未经过修改的，所以你可以发现支持和反对（或者不那么支持）的声音。

#### 3. [为什么你该摒弃 Java ，全面转向 Kotlin 语言？](https://www.oschina.net/news/85488/why-you-should-totally-switch-to-kotlin)
我想告诉你一个名为 Kotlin 的新的编程语言，以及为什么你要开始考虑使用它来开发你的下一个项目。我以前喜欢 Java ，但是去年我发现了 Kotlin ，只要有可能我就会用 Kotlin 来写代码。现在我实在无法想象有什么地方只有 Java 能做，而 Kotlin 不能的。

## Android开发
#### 1. [Zygote与内存](https://ivonhoe.github.io/2017/04/26/Zygote-2/)
当使用BitmapAnalyzer分析一个Android5.0+的Hello World App时你会dump出400+张图片，什么是BitmapAnalyzer？请看Android Bitmap的内存大小是如何计算的？这篇文章的介绍。分析仔细看一下可以发现，这些都是Android系统的主题资源图片，为什么会有这么多主题资源被加载？是不是选择其他的theme这些资源是会改变？不需要的无用资源能否避免被加载？How？毕竟单单Resources中sPreloadedDrawables所引用的Drawable就会占用10M以上的内存空间。

#### 2. [Handler的内存泄露及解决方法](http://dalufan.com/2015/08/28/android-handler-gc/)
常见的Handler的用法但是可能导致内存泄露,比如在旋转屏幕时该Activity重新绘制. 但是因为mHandler发送了一个延迟消息,所以消息队列持有mHandler对象,又由于new Runnable(){}持有外部类MainActivity的引用,以Activity所占内存并不能向期望的那样被回收,这样就可能会造成内存泄漏。

#### 3. [Android Handler Memory Leaks](http://techblog.badoo.com/blog/2014/08/28/android-handler-memory-leaks/)
Android uses Java as a platform for development. This helps us with many low level issues including memory management, platform type dependencies, and so on. However we still sometimes get crashes with OutOfMemory. So where’s the garbage collector?

#### 4. [学 Kotlin，看这一篇就够了](http://www.jianshu.com/p/51b404a155a4)
Kotlin学习资源合辑

#### 5. [Android热修复升级探索（二）](http://t.cn/RSjD5zg)
Android资源的热修复，就是在app不重新安装的情况下，利用下发的补丁包直接更新本app中的资源。

我们在开发阿里云移动热修复(Sophix)的过程中，对Android资源的加载原理做了深入的探究，最终在资源修复方法上取得了突破性进展！新的资源修复方法不论是在使用便捷性、补丁包大小以及运行时效率方面，相比其他实现都有巨大的优势。

#### 6. [【翻译】安卓架构组件(1)-App架构指导](http://www.jianshu.com/p/349f4791a668)
#### 7. [【翻译】安卓架构组件(2)-添加组件到你的项目中](http://www.jianshu.com/p/e4319fc52227)
#### 8. [【翻译】安卓架构组件(3)-处理生命周期](http://www.jianshu.com/p/5ada0d48855f)
#### 9. [【翻译】安卓架构组件(4)-LiveData](http://www.jianshu.com/p/13a855ceaf2b)
#### 10. [【翻译】安卓架构组件(5)-ViewModel](http://www.jianshu.com/p/e61f045126f7)
#### 11. [【翻译】安卓架构组件(6)-Room持久化类库](http://www.jianshu.com/p/587f48dccf0a)

## 专题栏目 － HTML JavaScript CSS
#### 1. [HTML 教程](http://www.runoob.com/html/html-tutorial.html)
#### 2. [HTML5 教程](http://www.runoob.com/html/html5-intro.html)
#### 3. [CSS 教程](http://www.runoob.com/css/css-tutorial.html)
#### 4. [CSS3 教程](http://www.runoob.com/css3/css3-tutorial.html)
#### 5. [JavaScript 教程](http://www.runoob.com/js/js-tutorial.html)
#### 6. [Bootstrap 教程](http://www.runoob.com/bootstrap/bootstrap-tutorial.html)
#### 7. [Vue.js 教程](http://www.runoob.com/vue2/vue-tutorial.html)
#### 8. [ECMAScript 6 入门](http://es6.ruanyifeng.com)
《ECMAScript 6 入门》是一本开源的 JavaScript 语言教程，全面介绍 ECMAScript 6 新引入的语法特性。
## 开源库&项目&工具
#### 1. [JAndFix](https://github.com/qiuba/JAndFix)
JAndFix is a tool for Android real-time hot fix base on JAVA.

#### 2. [MaterialChipsInput](https://github.com/pchmn/MaterialChipsInput)
Implementation of Material Design Chips component for Android

#### 3. [PasscodeView](https://github.com/hanks-zyh/PasscodeView)
Material Design PasscodeView for Android.

#### 4. [Timeline-View](https://github.com/vipulasri/Timeline-View)
Android Timeline View is used to display views like Tracking of shipment/order, steppers etc.

## 联系方式
* Email：yanghui1986527#gmail.com
* Github: https://github.com/snowdream
* Blog: http://snowdream.github.io/blog/
* 简书：http://www.jianshu.com/u/748f0f7e6432
* 云栖博客：https://yq.aliyun.com/u/snowdream86 
* QQ群: 529327615     
* 微信公众号:  sn0wdr1am    

![sn0wdr1am](https://static.dingtalk.com/media/lADOmAwFCs0BAs0BAg_258_258.jpg)
