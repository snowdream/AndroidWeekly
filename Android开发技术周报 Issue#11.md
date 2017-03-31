# Android开发技术周报 Issue#11

    声明：所有内容收集整理自网络。如有侵权，请联系删除。微信公众号上请点击“阅读原文”阅读完整版本。
    
## 业界新闻
#### 1. [个人开发者可申请小程序](https://mp.weixin.qq.com/cgi-bin/announce?action=getannouncement&key=1490627746&version=1&lang=zh_CN)
小程序开放个人开发者申请注册，个人用户可访问微信公众平台，扫码验证个人身份后即可完成小程序帐号申请并进行代码开发。

请访问：[微信公众平台](https://mp.weixin.qq.com/cgi-bin/registermidpage?action=index&lang=zh_CN)
  
#### 2. [天猫团队开源跨平台模块化 UI 界面开发框架 Tangram](https://www.oschina.net/news/83432/alibaba-opensource-tangram)
Tangram，七巧板，是天猫团队刚刚开源的跨平台模块化 UI 界面方案。据悉，之所以命名为 Tangram ，是希望它能像七巧板一样可以通过几块积木就搭出丰富多彩的界面。
  
## Android开发
#### 1. [移动应用设计：综述、导航和浏览](http://t.cn/R60XeGw)
应用程序现在是主流的提供内容和服务的方式，并已经广受用户信赖。但在一个已经高度被开发的市场里，一款移动应用如何做到有用，有意义并且有价值，以使客户满意并留存呢？ Google 的 UX 研究主管 Jenny Gove 为您详细介绍了创建一款优秀的移动应用的 25 条原则，我们会在这次连载中分批次为您逐一详述。

#### 3. [Android View进阶之RecyclerView 实现滑动删除和拖拽功能](http://t.cn/R60aGB3)
从Android 5.0开始，谷歌推出了新的控件RecyclerView，相对于早它之前的ListView，优点多多，功能强大，也给我们的开发着提供了极大的便利，今天自己学习一下RecyclerView轻松实现滑动删除及拖拽的效果。

#### 3. [实现一个带下拉弹簧动画的 ScrollView](http://www.jianshu.com/p/ce6497cada9c)
在刚推出的 Support Library 25.3.0 里面新增了一个叫 SpringAnimation 的动画，也就是弹簧动画。要是用它来做一个滑动控件下拉回弹的效果，应该不错吧。

#### 4. [Android 渲染优化](http://wuxiaolong.me/2017/03/26/Rendering/?hmsr=toutiao.io&utm_medium=toutiao.io&utm_source=toutiao.io)
Android系统每隔16ms发出VSYNC信号，触发对UI进行渲染，要每次渲染都成功，这样就必须达到流畅的画面所需要的60fps，否则会发生丢帧的现象，丢帧越多，用户明确感到卡顿。卡顿现象，由于复杂的布局或界面过度绘制未能在每帧16ms内完成导致的。本文讲解了渲染优化的技巧。

#### 5. [天猫 Android Tangram 的基础 —— vlayout](https://mp.weixin.qq.com/s?__biz=MzAxNjI3MDkzOQ==&mid=2654472702&idx=1&sn=a21256387cc06b2a1833589f71e9b54a)
vlayout 是手机天猫 Android 版内广泛使用的一个基础 UI 框架项目，提供了一个用于 RecyclerView 的自定义的 LayoutManger，可以实现不同布局格式的混排，目标是支撑客户端 native 页面的快速开发。它也是 Tangram 框架的基础模块，现已开源。

#### 6. [是时候和 Implict Broadcast 说再见了](https://zhuanlan.zhihu.com/p/26029881?hmsr=toutiao.io&utm_medium=toutiao.io&utm_source=toutiao.io)
Android O对于系统广播（Broadcast）的改变归根结底都是为了进一步的节省功耗。Google在Android Marshmallo(6.0, API level 23)中引入了Doze and App Standby来改进Android系统的电池表现。本文主要介绍了Android O中对Broadcast的改变。

#### 7. [Android内存优化总结&实践](https://mp.weixin.qq.com/s/2MsEAR9pQfMr1Sfs7cPdWQ)
Andorid内存优化一直是一个比较重要的话题，我们可以通过各种内存泄露检测组件，MAT查看内存占用，Memory Monitor跟踪整个App的内存变化情况, Heap Viewer查看当前内存快照, Allocation Tracker追踪内存对象的来源,以及利用崩溃上报平台从多个方面对App内存进行监控和优化。本文列举了一些常见的情况，介绍了Android内存优化的方案。

#### 8. [Android 优化APP 构建速度的17条建议](http://www.jianshu.com/p/a1cc8f2e0877?hmsr=toutiao.io&utm_medium=toutiao.io&utm_source=toutiao.io)
较长的构建时间将会减缓项目的开发进度，特别是对于大型的项目，app的构建时间长则十几分钟，短则几分钟，长的构建时间已经成了开发瓶颈，本篇文章根据Google官方文档，外加作者的一些理解，目的是提供一些提升app构建速度的优化建议。

## 开源库&项目&工具
#### 1. [Tangram-Android](https://github.com/alibaba/Tangram-Android/blob/master/README-ch.md)
Tangram是一套动态化构建 Native 页面的框架，它包含 Tangram Android、Tangram iOS，管理后台等一些列基础设施。本工程是 Tangram Android 的sdk 项目地址，底层依赖于vlayout 和 UltraViewPager。

#### 2. [AppMethodOrder](https://github.com/zjw-swun/AppMethodOrder)
一个能让你了解所有函数调用顺序的Android库（无需侵入式代码）

## 联系方式
* Email：yanghui1986527#gmail.com
* Github: https://github.com/snowdream
* Blog: http://snowdream.github.io/blog/
* 简书：http://www.jianshu.com/u/748f0f7e6432
* 云栖博客：https://yq.aliyun.com/u/snowdream86 
* QQ群: 529327615     
* 微信公众号:  sn0wdr1am    

![sn0wdr1am](https://static.dingtalk.com/media/lADOmAwFCs0BAs0BAg_258_258.jpg)
