# Android开发技术周报 Issue#17

    声明：所有内容收集整理自网络。如有侵权，请联系删除。微信公众号上请点击“阅读原文”阅读完整版本。

## 业界新闻
#### 1. [Google 正秘密开发第三款操作系统 Fuchsia](https://www.oschina.net/news/84581/google-fuchsia)
这是一款开源的、实时操作系统，被其称作Fuchsia。与Android和Chrome OS不同，Fuchsia不是基于Linux，它使用一个全新的、由谷歌开发的微内核，称作“Magenta”。

#### 2. [媲美 Google，腾讯推出自研图片编码格式 TPG](https://www.oschina.net/news/84579/learn-from-google-tencent-tpg)
近日，记者从国家知识产权局了解到，腾讯公司正式向国家知识产权局提交了一份关于图片编码技术的专利申请。此项专利被命名为TPG（Tiny  Portable  Graphics），在数据上TPG图片格式产生的文件大小明显小于JPG/JPEG、PNG、GIF、WEBP等业界主流的图片格式，处于世界领先水平。

#### 3. [JCP EC 投票否决 Java 模块化系统](https://www.oschina.net/news/84639/jcp-ec-vote-to-deny-jiasaw)
JCP Executive Committee 公布了对 Java Platform Module System（或称为 Jigsaw）的投票结果，以 10 票赞成 13 票反对否决了该提议。

投反对票的机构包括了 HPE（惠普企业）、Redhat、IBM、SAP、Twitter、Eclipse 基金会等。这一结果并不出人意料，在这之前，EC 成员 Redhat 和 IBM 公开谈论他们反对模块化系统的观点，认为会导致不兼容。

#### 4. [Java 9 又要延期？甲骨文撂狠话：强推！](https://www.oschina.net/news/84663/java-9-delayed)
甲骨文公司近日为了延期超过一年的Java 9而杠上IBM与Red Hat，甲骨文批评两家公司反对Java 9模组化系统的发展，令人失望。

## Android开发
#### 1. [Android APK 瘦身 - JOOX Music项目实战](http://t.cn/Ra2Q7wv)
JOOX Music是腾讯海外布局的一个音乐产品，2014年发布以来已经成为5个国家和地区排名第一的音乐App。东南亚是JOOX Music的主要发行地区，由于JOOX Music所面对的市场存在很多的低端机型，并且这些市场的网络环境相对来说是比较差的，为了提升下载转化率，对JOOX Music进行APK瘦身是必不可免的。

#### 2. [图片加载框架Universal-Image-Loader源码解析](http://t.cn/RaXQRZj)
可以说是安卓知名图片开源框架中最古老、使用率最高的一个了。一张图片的加载对于安卓应用的开发也许是件简单的事，但是如果要同时加载大量的图片，并且图片用于 ListView、GridView、ViewPager 等控件，如何防止出现OOM、如何防止图片错位（因为列表的View复用功能）、如何更快地加载、如何让客户端程序员用最简单的操作完成本来十分复杂的图片加载工作，成了全世界安卓应用开发程序员心头的一大难题，所幸有了Universal-Image-Loader，让这一切变得简单，从某种意义来讲，它延长了安卓开发者的寿命~

#### 3. [Android音量系统分析](http://t.cn/RaX8ZF0)
最近在处理一个蓝牙设备播放没有声音问题时，发现是设置音量的问题，顺便学习了一下Android系统的音量构架原理及设置方法。这里主要参考了rinswindqin同学写的有关音频及音量分析的文章，加了一些自己的理解及源代码分析。下面以Android 6.0为例来说明。

#### 4. [ToyBricks简介以及原理分析](http://t.cn/RaAesa1)
我始终认为，在高内聚，低耦合的原则下，进行组件化，模块化，插件化都是移动应用开发的趋势。

#### 5. [ToyBricks用户手册](http://t.cn/RaXRMwa)
ToyBricks是一个Android项目模块化的解决方案，主要包括四个部分，APT注解，APT注解处理器，ToyBricks插件（Gradle Plugin）,ToyBricks库。

#### 6. [如何优雅的使用EventBus?](http://www.jianshu.com/p/e00297348f17)
EventBus是一款针对Android优化的发布/订阅事件总线。可以替代广播、startActivityForResult、Handler、异步回调等来实现各组件间、组件与后台线程间的通信。它的优点是开销小，代码更优雅，以及将发送者和接收者解耦。

## 开源库&项目&工具
#### 1. [StatusBarUtil](https://github.com/laobie/StatusBarUtil)
这是一个为Android App 设置状态栏的工具类， 可以在4.4及其以上系统中实现 沉浸式状态栏/状态栏变色，支持设置状态栏透明度，满足你司设计师的各种要求(雾)。

![StatusBarUtil](https://github.com/laobie/StatusBarUtil/raw/master/img/use_in_fragment.gif)

#### 2. [Android-Image-Cropper](https://github.com/ArthurHub/Android-Image-Cropper)
Powerful (Zoom, Rotation, Multi-Source), customizable (Shape, Limits, Style), optimized (Async, Sampling, Matrix) and simple image cropping library for Android.

![Android-Image-Cropper](https://github.com/ArthurHub/Android-Image-Cropper/raw/master/art/demo.gif?raw=true)

#### 3. [CarouselPicker](https://github.com/GoodieBag/CarouselPicker)
A Carousel picker library for android which supports both text and icons . ✨

![CarouselPicker](https://raw.githubusercontent.com/GoodieBag/CarouselPicker/master/gif/gif_image_480.gif)

## 联系方式
* Email：yanghui1986527#gmail.com
* Github: https://github.com/snowdream
* Blog: http://snowdream.github.io/blog/
* 简书：http://www.jianshu.com/u/748f0f7e6432
* 云栖博客：https://yq.aliyun.com/u/snowdream86 
* QQ群: 529327615     
* 微信公众号:  sn0wdr1am    

![sn0wdr1am](https://static.dingtalk.com/media/lADOmAwFCs0BAs0BAg_258_258.jpg)
