# Android开发技术周报 Issue#6

    声明：所有内容收集整理自网络。如有侵权，请联系删除。

## 业界新闻
#### 1. [Android Studio 2.3 RC 1 发布](https://www.oschina.net/news/82060/android-studio-23-rc1-is-now-available)
Android Studio 2.3 RC 1 发布了，此版本包含一组小的重要错误修复。

#### 2. [Google发布Android Things开发者第二预览版](http://www.cnbeta.com/articles/583739.htm)
Google在2个月前发布了Android Things，该操作系统旨在为物联网设备提供“Android之力”的加持。今天，该公司又发布了第二个开发者预览版。新编译版本中包含了大量新特性，比如支持英特尔Edison和树莓派3硬件抽象层的USB音频（以及英特尔的 Joule 物联网开发板）。

## Android开发
#### 1. [Android权限机制与适配经验](http://t.cn/RiwROkA)
Android M已经发布一段时间了，市面上很多应用都已经适配Android M。权限机制，作为Android M的一大特性，受到了很多开发者的关注。本文主要分享了以下几个知识点的内容，1、Android权限机制关键知识点；2、QQ音乐对于权限的适配经验；3、近段时间以来遇到的一些Android权限方面的问题。OK，下面进入主题。

#### 2. [深入剖析Android中的ArrayMap](http://droidyue.com/blog/2017/02/12/dive-into-arraymap-in-android)
数据集合在任何一门编程语言中都是很重要的一部分，在Android开发中，我们会实用到ArrayList，LinkedList，HashMap等。其中HashMap是用来处理键值对需求的常用集合。而Android中引入了一个新的集合，叫做ArrayMap，为键值对存储需求增加了一种选择。本文深度剖析了ArrayMap的实现原理。

#### 3. [归纳AOP在Android开发中的几种常见用法](http://www.jianshu.com/p/2779e3bb1f14)
在软件业，AOP为Aspect Oriented Programming的缩写，意为：面向切面编程，通过预编译方式和运行期动态代理实现程序功能的统一维护的一种技术。AOP是OOP的有力补充。玩好AOP对开发App是有很大的帮助的，本文详细介绍了AOP在Android开发中的常见用法。

#### 4. [从json文件到炫酷动画-Lottie实现思路和源码分析](http://www.jianshu.com/p/81be1bf9600c)
Lottie是最近Airbnb开源的动画项目，支持Android、iOS、ReactNaitve三个平台，相关背景介绍可以参考之前的文章Airbnb开源炫酷动画库Lottie（译）－看看Airbnb的工程师怎么说。本文分析主要Lottie把json文件转为动画的思路和源码实现。文章首先介绍Lottie的基本使用，然后分析把json文件映射到动画的实现思路，最后分析Lottie的源码实现，这里分析的是Lottie-Android。

#### 5. [Android AOP之字节码插桩详解](http://mp.weixin.qq.com/s/SyFe2CgKW51ROAcFHd0a5Q)
本篇文章基于《网易乐得无埋点数据收集SDK》总结而成，关于网易乐得无埋点数据采集SDK的功能介绍以及技术总结后续会有文章进行阐述，本篇单讲SDK中用到的Android端AOP的实现。随着流量红利时代过去，精细化运营时代的开始，网易乐得开始构建自己的大数据平台。其中，客户端数据采集是第一步。传统收集数据的方式是埋点，这种方式依赖开发，采集时效慢，数据采集代码与业务代码不解藕。

#### 6. [Android神奇“控件”-RemoteViews](http://blog.csdn.net/wrg_20100512/article/details/53940485)
先从表层意思理解RemoteViews感觉它是一个view的集合，而且和远程有关系。那事实上它是什么呢？从官方注释说明可以看出，RemoteViews是用来描述一个视图的，它描述的这个视图将显示在另外一个进程中，这也就符合了RemoteViews中Remote这层含义。同时说明里也说了RemoteViews提供了一些基本的操作方法来修改它描述的那个视图的内容。听起来它还真像是个“控件”，那它真的是吗？

#### 7. [移动开发需要知道的像素知识『多图』](http://t.cn/RiwR11r)
像素（Pixel）对于WEB开发者来说很是熟悉，在PC互联网时代没少与其打交道。进入移动互联网之后，随着移动设备屏幕的解析度越来越高，衍生了一些关于屏幕和像素的一些新概念，比如DPI，DP，PT，Retina，4K等等，本文对这些概念做一个简单的介绍。

## 开源库&项目&工具
#### 1. [MagicCamera](https://github.com/wuhaoyu1990/MagicCamera)
Real-time Filter Camera&VideoRecorder And ImageEditor With Face Beauty For Android---包含美颜等40余种实时滤镜相机，可拍照、录像、图片修改

#### 2. [Alerter](https://github.com/Tapadoo/Alerter)
This library aims to overcome the limitations of Toasts and Snackbars, while reducing the complexity of your layouts.

#### 3. [mkloader](https://github.com/nntuyen/mkloader)
Beautiful and smooth custom loading views

#### 4. [MD360Player4Android](https://github.com/ashqal/MD360Player4Android)
It is a lite library to render 360 degree panorama video for Android. 

## 联系方式
* Email：yanghui1986527#gmail.com
* QQ群: 529327615     
* 微信公众号:  sn0wdr1am    

![sn0wdr1am](https://static.dingtalk.com/media/lADOmAwFCs0BAs0BAg_258_258.jpg)
