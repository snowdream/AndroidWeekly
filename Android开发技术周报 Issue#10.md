# Android开发技术周报 Issue#10

    声明：所有内容收集整理自网络。如有侵权，请联系删除。微信公众号上请点击“阅读原文”阅读完整版本。

## 业界新闻
#### 1. [O-MG，Google 发布 Android O 开发者预览版！](https://www.oschina.net/news/83135/first-preview-of-android-o)
今天，Google 对外推出了 Android O （Android 8.0）操作系统的首个开发者预览版，并可供下载。同时，Google 也表示该版本还有很多性能和稳定性的工作待完成，不建议消费者日常使用。

#### 2. [Android 原生开发工具包 NDK r14 发布](https://www.oschina.net/news/83136/android-ndk-r14)
NDK (Native Development Kit) ，Android 原生开发工具包，是一个包含 API、交叉编译器、链接程序、调试器、构建工具、文档和示例应用程序的综合工具集。
最新版本的 Android NDK r14，现在可供下载，也可通过 Android Studio 在 SDK 管理器中使用。

#### 3. [Google 又弃坑了，Jack+Jill vs. javac+dx](https://zhuanlan.zhihu.com/p/25814519)
Jack + Jill被搞出来是原本是取代 javac + dx的，也就去年的事情，当大家纷纷准备在build.gradle里面纠结要不要打开 `useJack` 的时候，Google说，未来为支持Java8新特性，不再考虑Jack/Jill。

## Android开发
#### 1. [在 Android Studio 2.2 中愉快地使用 C/C++](http://wl9739.github.io/2016/09/21/在-Android-Studio-2-2-中愉快地使用-C-C-md/)
本篇文章将会说明如何使用 Android Studio 来创建、配置 Android 项目，以支持 native code，以及将其运行到你的 app 中。

#### 2. [GDE专栏 | 一个完整的示例：Android Things和TensorFlow能擦出怎样的火花？](http://t.cn/R6JxwHs)
现在深度学习很火，那我们就在 Android Things 中，利用摄像头抓拍图片，让 TensorFlow 去识别图像，最后用扬声器告诉我们结果。

#### 3. [教你手写一个贝塞尔曲线效果的Loading View](http://www.jianshu.com/p/9c07c9409ccd)
BesselLoadingView是一个贝塞尔曲线效果的加载过渡动画。使用canvas绘制的自定义view。

#### 4. [图解View测量、布局及绘制原理](http://www.jianshu.com/p/3d2c49315d68)
Android中自定义View一直是一个高级的技能，入门比较难，看起来很高大上。想要学会自定义View,当然要理解View的测量、布局及绘制原理，本篇文章将以图表的形式讲解View的测量、布局及绘制原理。

#### 5. [美团点评移动网络优化实践](http://tech.meituan.com/SharkSDK.html)
网络优化对于App产品的用户体验至关重要，与公司的运营和营收息息相关。这里列举两个公开的数据：1.页面加载超过3秒，57%的用户会离开。2.Amazon页面加载延长1秒，一年就会减少16亿美金营收。在做网络优化前，我们首先要为网络通信质量设立一个标尺。在美团点评，监控团队开发了基于端到端的客户端监控平台。这里要先解释一下“端到端”的含义：是指请求从客户端发出到服务端响应返回的整个过程。它区别于后台服务监控，是一种从用户角度观察到的真实体验监控。

#### 6. [理解JobScheduler机制](http://gityuan.com/2017/03/10/job_scheduler_service/)
对于满足网络、电量、时间等一定预定条件而触发的任务，那么jobScheduler便是绝佳选择。JobScheduler主要用于在未来某个时间下满足一定条件时触发执行某项任务的情况，那么可以创建一个JobService的子类，重写其onStartJob()方法来实现这个功能。

#### 7. [Android热更新方案Robust开源，新增自动化补丁工具](https://mp.weixin.qq.com/s?__biz=MjM5NjQ5MTI5OA==&mid=2651746151&idx=1&sn=a6ab1365133ba3e0a2b082ad8240cd7e)
Robust热更新系统借鉴Instant Run原理，实现了一个兼容性更强而且实时生效的热更新方案。其基本思路是，Robust热更新系统在一个方法的入口处插入一段跳转代码，当发现某个方法出现bug就跳转执行补丁中的代码，略过原有代码的执行，否则执行原有方法体逻辑。

#### 8. [Android应用优化小手册](http://blog.csdn.net/dd864140130/article/details/62431927)
对我们技术从业者而言,很多时候时候不是我们不知道怎么做,而是不知道做什么?今天系统的总结自己关于如何对Android应用进行优化的一些经验,共计八个维度.

## 开源库&项目&工具
#### 1. [🍼Debug Bottle]()
Android Java / Kotlin 程序员开发调试工具。Debug Bottle的所有功能均建立在App的debug版本中，不会对release版本产生任何影响。Debug Bottle旨在提高开发效率，把控App质量。

![🍼Debug Bottle](https://raw.githubusercontent.com/kiruto/debug-bottle/1.1.x/screenshots/scalpel-view.png)

#### 2. [使用WebGL 2.0更快地渲染 3D](http://t.cn/R6JxxbF)
WebGL JavaScript API 将硬件加速 3D 图形技术带入网络。

#### 3. [Android可伸缩布局－FlexboxLayout(支持RecyclerView集成)](http://t.cn/R6JxXYU)
FlexboxLayout是一个Android平台上与CSS的 Flexible box 布局模块 有相似功能的库。Flexbox 是CSS 的一种布局方案，可以简单、快捷的实现复杂布局。FlexboxLayout可以理解成一个高级版的LinearLayout，因为两个布局都把子view按顺序排列。两者之间最大的差别在于FlexboxLayout具有换行的特性。

#### 4. [Robust](https://github.com/Meituan-Dianping/Robust)
新一代热更新系统Robust，对Android版本无差别兼容。无需发版就可以做到随时修改线上bug，快速对重大线上问题作出反应，补丁修补成功率高达99.9%。

## 联系方式
* Email：yanghui1986527#gmail.com
* Github: https://github.com/snowdream
* Blog: http://snowdream.github.io/blog/
* 简书：http://www.jianshu.com/u/748f0f7e6432
* 云栖博客：https://yq.aliyun.com/u/snowdream86 
* QQ群: 529327615     
* 微信公众号:  sn0wdr1am    

![sn0wdr1am](https://static.dingtalk.com/media/lADOmAwFCs0BAs0BAg_258_258.jpg)
