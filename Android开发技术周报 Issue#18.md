# Android开发技术周报 Issue#18

    声明：所有内容收集整理自网络。如有侵权，请联系删除。微信公众号上请点击“阅读原文”阅读完整版本。
    
## 业界新闻
#### 1. [欢呼声热烈 谷歌宣布 Kotlin 成 Android 开发一级语言](https://www.oschina.net/news/84938/android-o-release-with-kotlin)
谷歌宣布，将Kotlin语言作为安卓开发的一级编程语言。Kotlin由JetBrains公司开发，与Java 100%互通，并具备诸多Java尚不支持的新特性。谷歌称还将与JetBrains公司合作，为Kotlin设立一个非盈利基金会。


#### 2. [Android Studio 3.0 Canary 1 发布，支持 Kotlin 语言](https://www.oschina.net/news/84948/android-studio-3-0-canary1)
Android Studio 3.0 Canary 1 发布了。官方表示，这些一直在默默迭代中的功能本应是 Android Studio 2.4 Canaries 的一部分，但今天他们意识到这个版本添加了许多重要的功能，因此将版本改成了 Android Studio 3.0。Android Studio 3.0 Canary 1 三个主要的新特性：

* 一套新的应用程序性能分析工具，用于快速诊断性能问题

* 支持 Kotlin 编程语言

* 提升大型 app 项目的 Gradle 构建速度

#### 3. [谷歌正式发布 Android O 首个公测版](https://www.oschina.net/news/84943/whats-new-in-android-o-developer)
谷歌 I/O 2017 开发者大会今日正式召开，并公布了全新一代的安卓系统 Android O，目前首个公测版已经开放下载，但是官方尚未公布 Android O 的正式代号。

根据谷歌官方在 I/O 2017 开发者大会上的介绍，Android O 的更新可概括为两方面：一是“Fluid Experience（流畅体验）”，二是“Vitals（核心功能）”。前者主要是新系统的功能性部分，后者则更关注安全、性能等。

除此之外，谷歌还带来了一个 Android Go 的早期版本，专门针对具有 1GB 或更少内存的 Android 设备构建。

#### 4. [Glide 4.0.0 RC0 发布，Android 图片加载和缓存库](https://www.oschina.net/news/84926/glide-4-0-0-rc0)
Glide 4.0.0 RC0 发布了，Glide 是一个 Android 上的图片加载和缓存库，其目的是实现平滑的图片列表滚动效果。

本次的更新包含较多的更改，下面列出一些值得关注的亮点：

* 用户可以通过向 Glide 的 gh 页面分支提交 pull requests 来提供新的文档

* 一个新的可扩展生成的 API，允许通过添加新类型或自定义选项集来轻松定制 Glide 流畅的 API

* 大量简化的个人请求类型，确保选项始终如一，易于使用，即使您正在加载不同类型的资源

* 各种性能改进，包括在下载采样图像时大量减少垃圾，更加智能的默认磁盘缓存策略，以及加载 GIF 时性能的改进

* 改进了视图大小和布局的处理，特别是在 RecyclerView 中

## Android开发
#### 1. [Android热修复升级探索](http://t.cn/RaRCACt)
前段时间，Android平台上涌现了一系列热修复方案，如阿里的Andfix、微信的Tinker、QQ空间的Nuva、手Q的QFix等等。

其中，Andfix的即时生效令人印象深刻，它稍显另类，并不需要重新启动，而是在加载补丁后直接对方法进行替换就可以完成修复，然而它的使用限制也遭遇到更多的质疑。

我们也对代码的native替换原理重新进行了深入思考，从克服其限制和兼容性入手，以一种更加优雅的替换思路，实现了即时生效的代码热修复。

#### 2. [FlexboxLayout——实现灵活多变的瀑布流](http://www.jianshu.com/p/8060f7623f1c)
之前看到一个很炫酷的布局：FlexboxLayout，可以很方便地实现瀑布流的效果。今天正好用到项目中，对FlexboxLayout进行一个简单的学习。

#### 3. [Android 中使用持续集成](https://zhuanlan.zhihu.com/p/26758264)
Continuous Integration - 持续集成，持续集成是一种软件开发实践，通过自动化的构建（包括编译、发布和自动化测试）来验证，从而帮助尽快发现集成错误。

#### 4. [okhttp内核剖析](http://www.jianshu.com/p/9ed2c2f2a52c)
本文是一篇介绍okhttp内核原理的文章，由于okhttp源码特别特别复杂，类涉及较多，所以导致本文非常长。本文作者非常用心，还为读者录制了录制了跟文章同步的视频。

#### 5. [Android 模块化探索与实践](http://baronzhang.com/blog/Framework/Android-模块化探索与实践/)
为了降低大型软件复杂性和耦合度，同时也为了适应模块重用、多团队并行开发测试等等需求，模块化在 Android 平台上变得势在必行。

## 专题栏目 － Kotlin
#### 1. [Getting started with Android and Kotlin](http://kotlinlang.org/docs/tutorials/kotlin-android.html)
This tutorial walks us through creating a simple Kotlin application for Android using Android Studio. 

#### 2. [Android Frameworks Using Annotation Processing](http://kotlinlang.org/docs/tutorials/android-frameworks.html)
This tutorial describes the usage of popular Android frameworks and libraries that use annotation processing with Kotlin. 

#### 3. [Kotlin Reference](http://kotlinlang.org/docs/reference/)
Provides a complete reference to the Kotlin language and the standard library.

#### 4. [Kotlin：Android世界的Swift](http://www.infoq.com/cn/news/2015/06/Android-JVM-JetBrains-Kotlin)
Kotlin是一门与Swift类似的静态类型JVM语言，由JetBrains设计开发并开源。与Java相比，Kotlin的语法更简洁、更具表达性，而且提供了更多的特性，比如，高阶函数、操作符重载、字符串模板。它与Java高度可互操作，可以同时用在一个项目中。

#### 5. [awesome-kotlin](https://github.com/KotlinBy/awesome-kotlin#android-libraries)
Kotlin相关类库索引大全

#### 6. [kotlinpoet](https://github.com/square/kotlinpoet)
A Kotlin API for generating .kt source files.

#### 7. [ToyBricks简介以及原理分析](http://t.cn/RaAesa1)
我始终认为，在高内聚，低耦合的原则下，进行组件化，模块化，插件化都是移动应用开发的趋势。

#### 8. [ToyBricks用户手册](http://t.cn/RaXRMwa)
ToyBricks是一个Android项目模块化的解决方案，主要包括四个部分，APT注解，APT注解处理器，ToyBricks插件（Gradle Plugin）,ToyBricks库。

#### 9. [使用Kotlin开发Android 创建工程与配置](http://www.jianshu.com/p/1f1d1000f146)
今天早上谷歌I/O 2017大会，Kotlin成为了Android开发的官方语言，之前就有听过Kotlin，但并没有实际使用过，现在看来是该了解了。

#### 10. [使用Kotlin优雅的开发Android应用](http://www.jianshu.com/p/4f60932d46ff)
今天的这篇文章带你学习使用Kotlin开发Android应用，并对比我们传统语言Java，让你真真切切的感受到他的美和优雅。

#### 11. [《Kotlin for android developers》中文版翻译](https://wangjiegulu.gitbooks.io/kotlin-for-android-developers-zh/content/)
在这本书中，我会使用Kotlin作为主要的语言来开发一个android应用。方式是通过开发一个应用来学习这门语言，而不是根据传统的结构来学习。我会在感兴趣的点停下来通过与Java1.7对比的方式讲讲Kotlin的一些概念和特性。用这种方法你就能知道它们的不同之处，并且知道哪部分语言特性可以让你提高你的工作效率。

## 开源库&项目&工具
#### 1. [ParticleTextView](https://github.com/Yasic/ParticleTextView)
一个用粒子动画显示文字的 Android 自定义 View

#### 2. [JetBrains/kotlin](https://github.com/JetBrains/kotlin)
The Kotlin Programming Language http://kotlinlang.org/

#### 3. [kotlinpoet](https://github.com/square/kotlinpoet)
A Kotlin API for generating .kt source files.

#### 4. [Kotlin/anko](https://github.com/Kotlin/anko)
Pleasant Android application development

#### 5. [Kotlin Playground](https://try.kotlinlang.org/)
Try Kotlin right in the browser.

## 联系方式
* Email：yanghui1986527#gmail.com
* Github: https://github.com/snowdream
* Blog: http://snowdream.github.io/blog/
* 简书：http://www.jianshu.com/u/748f0f7e6432
* 云栖博客：https://yq.aliyun.com/u/snowdream86 
* QQ群: 529327615     
* 微信公众号:  sn0wdr1am    

![sn0wdr1am](https://static.dingtalk.com/media/lADOmAwFCs0BAs0BAg_258_258.jpg)
