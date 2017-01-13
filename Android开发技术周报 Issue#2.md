# Android开发技术周报 Issue#2

## 业界新闻
#### 1. [Android Studio 2.3 Beta2 发布](https://www.oschina.net/news/80878/android-studio-2-3-beta2)
Android Studio 2.3 Beata2 发布了。
新的或值得注意的变化：
* 从 Android Studio 2.3 Beta 1 的 Gradle 3.3  RC1 移动到 Gradle 3.3  
* 如果你是本地开发，请更新 LLDB to 2.3.3614996

#### 2. [Chrome 56 Android 版已引入 WebVR API](https://www.oschina.net/news/80872/chrome-56-android-can-use-webar-api)
据谷歌开发者博客透露，Chrome 56 for Android 现已发布 Beta 测试版，开发者可以注册开源试用版，后者支持 WebVR API 和 GamePad API 扩展程序。

#### 3. [微信小程序正式上线 可置于聊天窗口顶部](http://tech.qq.com/a/20170109/000599.htm)
历经一年的等待后，小程序在2017年1月9日凌晨终于揭开神秘面纱，正式上线。

![微信小程序正式上线](http://img1.gtimg.com/tech/pics/hv1/183/35/2177/141568533.png)

#### 4. [Google 提供 Fastboot 和 ADB 单独下载服务](https://www.oschina.net/news/80796/google-open-platform-tools)
在许多 Android 用户多次呼吁之后，Google 终于将 ADB 和 Fastboot 作为单独的文件提供给用户下载。以前这些文件只包含在大尺寸的 Android SDK 或 Android Studio 当中提供给用户，现在这种变化意味着它们现在比以往更快，更容易执行和侧载。

![Google 提供 Fastboot 和 ADB 单独下载服务](https://static.oschina.net/uploads/space/2017/0107/225422_zT9F_2896879.jpg)

#### 5. [Google 通知：Android 通知中心风格必须统一](https://www.oschina.net/news/80947/android-notification-center-style-must-be-uniform)
Android 7.0 Nougat 加入了对于通知的直接回复、整合，而第三方 ROM 必须照样画葫芦。这意味着无论购买哪家的 Android 手机，通知中心都会是一个模样。

这一规定将从 Android 7.1 开始执行。如果厂商违反规定，将无法访问 Google Play 和其他服务。

![Google 通知：Android 通知中心风格必须统一](https://static.oschina.net/uploads/space/2017/0113/101725_1PzR_2896879.png)
## Android开发
#### 1. [系统相机相册获取图片并裁剪之Android N适配](http://www.jianshu.com/p/dffd7533b636)
本篇主要对Android调用系统相机裁剪及适配Android N的总结

#### 2. [Android 开发人员必知的50个秘诀、技巧和资源](https://www.oschina.net/news/80873/50-tips-tips-and-resources-android-developers-must-know)
作者撰写本文的初衷，是为了罗列出Android Studio有用的提示、技巧、快捷方式和参考资源，将提高您的整体效率和操作性能。


#### 3. [用AndroidStudio开发自定义 Gradle plugin](http://t.cn/RM9YIZq)
本文内容包括: 
* 利用AndroidStudio,编写自定义Gradle plugin
* MavenDeployer 发布plugin
* 使用Gradle plugin

#### 4. [Input系统—ANR原理分析](http://gityuan.com/2017/01/01/input-anr/)
当input事件处理得慢就会触发ANR，那ANR内部原理是什么，哪些场景会产生ANR呢。 “工欲善其事必先利其器”，为了理解input ANR原理，前面几篇文章疏通了整个input框架的处理流程，都是为了这篇文章而做铺垫。在正式开始分析ANR触发原理以及触发场景之前，先来回顾一下input流程。

#### 5. [Jack & Jill，Android 新的编译工具链](https://zhuanlan.zhihu.com/p/24708104?hmsr=toutiao.io&utm_medium=toutiao.io&utm_source=toutiao.io)
在2016年随着Android N的发布，Google同时发布了新的编译工具链称之为Jack和Jill。Jack全名为Java Android Compiler Kit，Jill则是Jack Intermediate Library Linker。Jack主要负责将Java代码直接编译为Dalvik字节码等工作，Jill则是对.class文件做处理，生成.jack文件再交由Jack处理。本文对Jack、Jill进行了简单介绍。

#### 6. [Android性能优化：使用Lint优化代码、去除多余资源](http://blog.csdn.net/u011240877/article/details/54141714)
Lint是Android Studio提供的代码扫描分析工具，它可以帮助我们发现代码结构和质量问题，同时提供一些解决方案，而且这个过程不需要我们手写测试用例。Lint会根据预先配置的检测标准检查Android项目的源文件，发现潜在的bug或者可以优化的地方。Lint就像是一个洁癖患者，虽然可以让我们代码干净许多，但是如果真要把它提示的全解决，恐怕需要很大的工作量。通过本文，大家能够更加了解Lint的工作方式及其使用方法。

#### 7. [Android上如何实现矩形区域截屏](http://www.jianshu.com/p/0462dae4c808?hmsr=toutiao.io&utm_medium=toutiao.io&utm_source=toutiao.io)
对屏幕进行截屏并裁剪有两种方式：早截图和晚截图。早截图，就是先截取全屏，再让用户对截取到的图片进行修改；与之相对的，晚截图，就是先让用户在屏幕上划好区域，再进行截图和裁剪。其实两者并没有什么太大的区别，本文详细介绍了实现晚截图的方法。

#### 8. [Gradle的Build Scans是什么功能？](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=2651113007&idx=1&sn=a988037902605fc1691cd4b0aebb0efd)
2016年8月份，Gradle团队发布了Gradle 3.0版本，同时，引入了Gradle云服务（Gradle Cloud Services）。该服务“通过为Gradle构建工具增加新功能，并从新的角度分析你或你团队项目构建的过程，来提升自动化构建的效率和生产力”。其中第一个提供的云服务是Build Scans功能，该功能为免费功能。

#### 9. [沪江学习Android端重构实践](http://mp.weixin.qq.com/s?__biz=MzA3ODg4MDk0Ng==&mid=2651113015&idx=1&sn=8a83441294728480567d5d44ad53062c)
对于大的架构重构，相信每个公司都很谨慎。沪江学习的原则是将重构融合在每次迭代中，逐步优化代码的结构。这次针对整个应用的架构的调整背景是，公司移动开发部门的人数和项目越来越多，当初设计的移动端的架构让项目的依赖关系越来越复杂，维护成本也越来越高。刚好赶上公司产品的特别需求，作者的团队决定梳理并优化一下整个项目结构。在实施过程中，依然坚持将整个重构的过程融合在每个迭代中，逐步完成一次大的架构升级。

#### 10. [Android性能优化-过度绘制解决方案](http://www.jianshu.com/p/cc893397dc9f)

![Android性能优化-过度绘制解决方案](http://upload-images.jianshu.io/upload_images/4307880-226e5029d6c83b8d.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

#### 11. [[干货]一种快速毛玻璃虚化效果实现--Android](http://www.jianshu.com/p/7ae7dfe47a70)
在android设备上快速实现毛玻璃效果

![毛玻璃](http://upload-images.jianshu.io/upload_images/281665-7d8e09155f0baf0e.png?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)

## 开源库&项目&工具
#### 1. [SimpleCropView](https://github.com/IsseiAoki/SimpleCropView)
A simple image cropping library for Android.

![SimpleCropView](https://camo.githubusercontent.com/4543749a82bbbcf158fe81e593c85aabeca4fe1b/68747470733a2f2f7261772e6769746875622e636f6d2f77696b692f4973736569416f6b692f53696d706c6543726f70566965772f696d616765732f312e312e302f64656d6f5f62617369635f75736167652e676966)

#### 2. [MarqueeViewLibrary](https://github.com/gongwen/MarqueeViewLibrary)
一个帮您快速实现跑马灯效果的library

![MarqueeViewLibrary](https://github.com/gongwen/MarqueeViewLibrary/raw/master/screenshot/screen_shot.gif)

#### 3. [ShimmerRecyclerView](https://github.com/sharish/ShimmerRecyclerView)
A custom recycler view with shimmer views to indicate that views are loading. 

![ShimmerRecyclerView](https://github.com/sharish/ShimmerRecyclerView/raw/master/screenshots/list_demo.gif)

#### 4. [手把手教你搭建属于自己的博客](http://t.cn/RM9dLoL)
自己搭建博客的话，样式的选择也比较自由，可以自己选择，不需要受限于各大平台。

大概可以分为以下几个步骤：

1. 搭建环境准备（包括 node.js 和 git 环境，gitHub 账户的配置）

2. 安装Hexo

3. 配置Hexo

4. 怎样将 Hexo 与 github page 联系起来

5. 怎样发布文章

6. 主题推荐

7. 主题Net的简单配置

8. 添加 sitemap 和 feed 插件

9. 添加 404 公益页面


## 联系方式
* Email：yanghui1986527#gmail.com
* QQ群: 529327615     
* 微信公众号:  sn0wdr1am    

![sn0wdr1am](https://static.dingtalk.com/media/lADOmAwFCs0BAs0BAg_258_258.jpg)
