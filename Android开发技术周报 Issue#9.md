# Android开发技术周报 Issue#9

    声明：所有内容收集整理自网络。如有侵权，请联系删除。

## 业界新闻
#### 1. [Google 宣布 Android 将加入 Java 8 的原生支持](https://www.oschina.net/news/82929/future-of-java-8-language-feature)
Google 表示已决定将把对 Java 8 语言特性的支持直接添加到当前的 javac 和 dx 工具集中，并不再推荐使用 Jack toolchain。今后，Android 构建系统将提供对 Java 8 语言特性的原生支持。依赖于 Java Class 文件格式的现有工具和插件将能继续工作。

#### 3. [谷歌称已经修复很多被 CIA 利用的漏洞](https://www.oschina.net/news/82702/google-announce-fixed-bug-cia-attacked)
昨天“维基解密”网站发布了美国中央情报局(CIA)文件黑客项目的数千份文件。 据外媒报道，谷歌公司今天表示，其已经修复了遭曝光CIA文件中确定的Chrome和Android平台中的很多漏洞。

#### 4. [阿里宣布 Atlas 开源，提升大规模团队移动开发效率](https://www.oschina.net/news/82821/alibaba-opensource-atlas)
继 Weex 之后，阿里在移动技术领域又有开源大动作。
3月13日，手机淘宝安卓客户端容器化框架 Atlas 正式宣布开源。Atlas 由阿里巴巴移动团队自研，以容器化思路解决大规模团队协作问题，实现并行开发、快速迭代和动态部署，适用于 Android 4.x 以上系统版本的大小型 App 开发。

#### 5. [Android Studio 2.4 Preview 1 发布](https://www.oschina.net/news/82889/android-studio-2-4-preview1)
Android Studio 2.4 Preview 1 发布了，这是一个早期的构建版本，所以在未来几周会有更多的更新。

#### 6. [Kotlin 1.1.1 发布，基于 JVM 的编程语言](https://www.oschina.net/news/82883/kotlin-1-1-1-is-out)
Kotlin 1.1.1 发布了，这也是 Kotlin 1.1 的首次 bug 修复版本。
本次更新的主要重点是解决不正确代码生成的回归.

## Android开发
#### 1. [yoga初探](http://t.cn/R6v9Kxq)
yoga本是Facebook在React Native里引入的一种跨平台的基于CSS的布局系统，它实现了Flexbox规范，随着该系统不断完善，Facebook对其进行重启发布，并取名为yoga。详情可以参考https://facebook.github.io/。

#### 2. [Atlas-手淘组件化框架的前世今生和未来的路](http://t.cn/R6vCL8w)
在手机淘宝，Atlas是一个扎根于Android客户端的一个组件化容器框架，相比神话中用手和头支撑起苍天的泰坦神族，Atlas在手淘默默无闻地承载着手淘上丰富业务的运行，伴随着数不清的功能在用户手中经历新老交替。

#### 3. [NDK Maping 发布啦](http://t.cn/R6vCKqx)
NDK Mapping 的主要工作就是完成 class 从 JVM 层到 JNI 层的映射。通常情况下，当我们进行 JNI 开发时，无可避免的要进行类的传递操作，而 JNI 提供的 API 却让代码简单不起来，大量的容易出错的体力劳动也是这么来的。

#### 4. [手机QQ Hybrid的架构演进](http://mp.weixin.qq.com/s/J_7uiET3p7MfJTq5m59AUw)
现在主流的hybrid还是H5 + native。H5在native中很明显的问题大家都看得到，比如打开应用的时候要等很久的页面loading。还有一点是每次打开H5都涉及到网络交互、文件下载，这些操作会消耗用户的流量，如果流量消耗大用户也会不高兴。本文给大家分享的内容主要是介绍QQ会员团队如何在页面打开时间以及用户流量方面所做的优化，分别对应sonic和reshape的两个自主技术框架。

#### 5. [React Native for Android异常处理概览](http://mp.weixin.qq.com/s/aWuenpGOKug4fovT5uKXTQ)
研究RN框架异常的动机在于，需要建立起一套针对性的容错机制，毕竟它还是一个不够成熟的框架。期望能够做到的效果就是，对于每一个RN页面的启动，能够在进入页面至退出页面期间侦测所有发生的RN相关的崩溃，然后根据崩溃来考虑该页面是否该有降级策略、判断框架是否真的能够支持稳定迭代。本文从启动期和运行期两方面介绍了RN的异常方案。

#### 6. [Android Drawable完全解析（一）：Drawable源码分析系列](http://www.jianshu.com/p/c56b762210f2)
Android开发中，Drawable几乎无处不在，Drawable涉及的面很广，尤其是竟然有那么多的继承类。我们常用的有ColorDrawable、StateListDrawable、BitmapDrawable等很有限的几个子类，大多数开发者对于Drawable的应用还是太零散了。因此作者写了关于Drawable的系列文章，从源码的角度详细分析了Drawable的实现。

#### 7. [Android中一个简单有用的发现性能问题的方法](http://droidyue.com/blog/2017/03/13/a-small-trick-to-detect-time-consuming-task/)
在Android中，性能优化是我们持之不懈的工作。这其中，在主线程执行耗时的任务，可能会导致界面卡顿，甚至是ANR（程序未响应）。当然Android提供了很多优秀的工具，比如StrictMode，Method Tracing等，便于我们检测问题。本文介绍了一个更加简单有效的方法。相比StrictMode来说更加便于发现问题，相比Method Tracing来说更加容易操作。

## 开源库&项目&工具
#### 1. [Atlas](http://atlas.taobao.org)
Atlas - 带你重返App开发的田园时代

#### 2. [BlockCanaryEx](https://github.com/lqcandqq13/BlockCanaryEx)
比起BlockCanary，BlockCanaryEx可以知道项目中所有方法的执行时间和次数。在app发生卡顿时，可以将耗时的方法直接展示给开发者。

#### 3. [FadingTextView](https://github.com/rosenpin/FadingTextView)
A TextView that changes its content automatically every few seconds


## 联系方式
* Email：yanghui1986527#gmail.com
* Github: https://github.com/snowdream
* Blog: http://snowdream.github.io/blog/
* 简书：http://www.jianshu.com/u/748f0f7e6432
* 云栖博客：https://yq.aliyun.com/u/snowdream86 
* QQ群: 529327615     
* 微信公众号:  sn0wdr1am    

![sn0wdr1am](https://static.dingtalk.com/media/lADOmAwFCs0BAs0BAg_258_258.jpg)
