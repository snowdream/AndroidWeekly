# Android开发技术周报 Issue#25

    声明：所有内容收集整理自网络。如有侵权，请联系删除。微信公众号上请点击“阅读原文”阅读完整版本。
    
## 业界新闻
#### 1. [360 宣布开源 RePlugin ，让插件化飞入寻常应用家](https://www.oschina.net/news/86322/360-opensource-replugin)
奇虎 360 宣布于今日正式开源其插件化方案 RePlugin 。

RePlugin 是一套完整的、稳定的、适合全面使用的，占坑类插件化方案，于 2014 年中旬从 360 手机卫士团队产生，并正式在卫士上启用。360 表示 RePlugin 无论大小项目均可使用，稳定与灵活兼得，目前 360 公司几乎所有的亿级用户量的 APP ，以及多款主流第三方 APP ，都采用了 RePlugin 方案。

#### 2. [滴滴宣布开源 Android 端插件化框架 VirtualAPK](https://www.oschina.net/news/86317/didi-opensource-virtualapk)
滴滴于今天正式宣布开源其 Android 插件化框架 —— VirtualAPK ，这也是滴滴公司的首个对外开源项目。

#### 3. [WCDB 1.0.2 发布，腾讯开源的移动数据库框架](https://www.oschina.net/news/86493/wcdb-1-0-2)
WCDB 1.0.2 已发布，WCDB 是腾讯开源的一个高效、完整、易用的移动数据库框架，基于 SQLCipher ，支持 iOS、macOS 和 Android 。

#### 4. [Mars 1.1.7 发布，微信跨平台跨业务的终端基础组件](https://www.oschina.net/news/86529/mars-1-1-7)
Mars 是微信官方的跨平台跨业务的终端基础组件，目前已接入微信 Android、iOS、Mac、Windows、WP 等客户端。

![Mars](https://static.oschina.net/uploads/space/2017/0707/075550_luMz_2896879.png)

## Android开发
#### 1. [深入探索Android热修复技术原理](http://t.cn/RKAjVCB)
读完本书，你将会对Android热修复技术有很深刻的认识，不仅能很大改进工作效率，对于系统底层原理的理解和今后的开发工作都有很大帮助。目前热修复原理还经常出现在高级Android技术岗位的面试题里，对付它们你也将得心应手。
 
对了，你甚至可以自己实现一个完善的热修复框架，对系统底层原理有更深的理解和掌握。
![深入探索Android热修复技术原理Â](https://mmbiz.qpic.cn/mmbiz_jpg/Z6bicxIx5naLxCKLR3YbOVpTGzHQwI7oHPt2d4qVrGFGa8lb2vZApsQ8dRPtQjQZRib2hGxJTDsHKqmjRiamdNVZA/640?wx_fmt=jpeg&wxfrom=5&wx_lazy=1)

#### 2. [Kotlin 泛型详解](http://t.cn/RKAlaVx)
Kotlin 100% 与 Java 兼容，所以抛开语言表面上面的种种特质之外，背后的语言逻辑或者说“灵魂”与 Java 总是想通的。本文只涉及 Kotlin Jvm，Kotlin Js、Kotlin Native 的具体实现可能有差异。

#### 3. [Android 平台 Native 代码的崩溃捕获机制及实现](http://t.cn/RKAlR9X)
在Android平台，native crash一直是crash里的大头。native crash具有上下文不全、出错信息模糊、难以捕捉等特点，比java crash更难修复。

#### 4. [GIF简述及其在QQ音乐的应用](http://t.cn/RKAjQKq)
GIF(Graphics Interchange Format)是CompuServe公司在1987年开发的图像文件格式，原义是图像互换格式。GIF是一种基于LZW算法的连续色调的无损压缩格式，其压缩率一般在50%左右，它不属于任何应用程序。

#### 5. [Android NDK开发扫盲及最新CMake的编译使用](http://www.jianshu.com/p/6332418b12b1)
本篇文章旨在简介 Android 中 NDK 是什么以及重点讲解最新 Android Studio 编译工具 CMake 的使用。

#### 6. [WebView 安全性的新功能](https://mp.weixin.qq.com/s/DZY_rHW2RyV-Q-FA3pH--w)
应用程序中对于外部和不信任内容的处理经常是重要的功能之一。新闻阅读器显示头条新闻文章、购物应用展示销售物品的目录。作为处理不信任内容而带来的相关风险是一个攻击者能够损害您的应用程序主要的方式之一，即传递给你错误格式的内容。

#### 7. [深入理解 Android 控件](https://pqpo.me/2017/07/01/learn-android-view/)
本篇文章主要通过源码讲述 Android 控件系统，包括输入事件是如何产生的， View 是如何绘制的，输入事件是如何传递给 View 的，Window token 与 type 之间的联系等。整个系统比较复杂，每个部分只能点到为止，有兴趣可以继续深入，主要是让读者对 Android 控件系统有一个大体的认识。

## 开源库&项目&工具
#### 1. [Qihoo360/RePlugin](https://github.com/Qihoo360/RePlugin)
RePlugin是一套完整的、稳定的、适合全面使用的，占坑类插件化方案。

#### 2. [VirtualAPK](https://github.com/didi/VirtualAPK)
A powerful and lightweight plugin framework for Android

#### 3. [MaterialDrawer 5.9.4 发布，Android 侧滑显示控件](https://www.oschina.net/news/86384/materialdrawer-5-9-4)
MaterialDrawer 5.9.4 已发布，MaterialDrawer 是一个类似 Google 官方 NavigationView 侧滑显示控件, 能够实现跟 NavigationView 一样的效果, 同时还支持自定义效果, 自由度非常高。

![MaterialDrawer](http://static.oschina.net/uploads/img/201603/17172136_am8K.jpg)

#### 4. [SmartRefreshLayout](https://github.com/scwang90/SmartRefreshLayout)
Android智能下拉刷新框架，支持越界回弹，集成了几十种炫酷的Header和 Footer https://segmentfault.com/a/1190000010066071

## 联系方式
* Email：yanghui1986527#gmail.com
* Github: https://github.com/snowdream
* Blog: http://snowdream.github.io/blog/
* 简书：http://www.jianshu.com/u/748f0f7e6432
* 云栖博客：https://yq.aliyun.com/u/snowdream86 
* QQ群: 529327615     
* 微信公众号:  sn0wdr1am    

![sn0wdr1am](https://static.dingtalk.com/media/lADOmAwFCs0BAs0BAg_258_258.jpg)
