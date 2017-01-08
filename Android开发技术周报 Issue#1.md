# Android开发技术周报 Issue#1

## 业界新闻
#### 1. [“OK, Google” 开放体验，可以为你的应用服务了](https://www.oschina.net/news/80777/ok-google-open-experience)
![OK, Google](https://static.oschina.net/uploads/space/2017/0107/223953_Qnv7_2896879.gif)
 
#### 2. [谷歌与菲亚特合作开发新款 Android 车载系统](https://www.oschina.net/news/80625/google-cooperate-with-fiat-to-develop-android-vehicle-system)
北京时间 1 月 3 日消息，据外媒报道，谷歌和菲亚特-克莱斯勒汽车公司周一在国际消费电子展(CES)开幕前宣布，两家公司已在合作开发一款基于 Android 系统的新版车载信息娱乐系统。

#### 3. [Google Play服务将最低支持API级别14](http://dwz.cn/4ZU0Q3)
Google Play 服务客户端内容库及 Firebase for Android 客户端内容库的 10.0.0 版本将是支持 Android API 级别 9（Android 2.3，Gingerbread）的最后版本。这些内容库的下一计划版本是 10.2.0，该版本会将支持的最低 API 级别从 9 提升至 14（Android 4.0.1，Ice Cream Sandwich）。此变更将于 2017 年初实施。 

## Android开发
#### 1. Google分享系列
* [Android 7.x的新增功能 (Google开发者大会演讲PPT&视频)](http://dwz.cn/4ZU4VG)
* [Android开发工具中的新增功能 (Google开发者大会演讲PPT&视频)](http://dwz.cn/4ZUaYw)
* [“哎呀！我的 Android 应用程序又崩溃了！” (Google开发者大会演讲PPT&视频)](http://dwz.cn/4ZUgwG)
* [Android开发中的电量和内存优化 (Google开发者大会演讲PPT&视频)](http://dwz.cn/4ZUiIF)
* [Vulkan-专为Android打造的高性能3D图像API (Google开发者大会演讲PPT&视频)](http://dwz.cn/4ZUjLB)

#### 2. [微信终端跨平台组件 mars 系列](http://t.cn/RIB70MM)
2012 年中，微信支持包括 Android、iOS、Symbian 三个平台。但在各个平台上，微信客户端没有任何统一的基础模块。2012 年的微信正处于高速发展时期，各平台的迭代速度不一、使用的编程语言各异，后台架构也处在不断探索的过程中。多种因素使得各个平台基础模块的实现出现了差异，导致出现多次需要服务器做兼容的善后工作。网络作为微信的基础，重要性不言而喻。

#### 3. [Android无处不在，Android开发者大有可为](http://t.cn/RIE1ott)
Android Things 正式接替 Brillo 亮相，名称的改变带来了什么新的内容，广大 Android 开发者如何进入这一新的领域，通过本文，你不仅会了解 Android Things 的来龙去脉，也会直接通过代码来体验开发带给你的魅力。

#### 4. [HttpResponseCache原理分析](http://qianzui.github.io/blog/2015-03-29-httpresponsecache-source-code-analysis/)
从Android4.0(API 14)开始，SDK源码中新增了一个类:android.net.http.HttpResponseCache.使用这个类可以很方便的对HTTP和HTTPS请求实现cache，所有的缓存逻辑再也不用自己写了，只要你使用HttpURLConnection或者HttpsURLConnection作为默认的网络请求库(也是Google官方建议使用的)，底层默认帮你实现的缓存的管理，不支持HttpClient。

#### 5. [贝塞尔Loading——化学风暴](http://dwz.cn/4ZUWpc)
 谈到贝塞尔曲线，很多人会觉得高逼格、复杂、头疼，实则不然，贝塞尔曲线经过android封装，已经显得娇俏可爱，简单好用，之前一些红极一时的效果也均是由其打造，比如QQ的“一键退潮”效果、电子书曲面翻页效果…… 现在咱们就用贝塞尔曲线一起从0到1打造一个拥有极致体验、清秀灵动的GABottleLoading效果
 
#### 6. [RecyclerView 必知必会](http://dwz.cn/507FK7)
 RecyclerView是Android 5.0提出的新UI控件，可以用来代替传统的ListView。

#### 7. [手游热更新方案xLua开源：Unity3D下Lua编程解决方案](http://dwz.cn/507Iol)
 xLua是Unity3D下Lua编程解决方案，自2016年初推广以来，已经应用于十多款腾讯自研游戏，凭借其出色的性能，易用性，扩展性而广受好评。

## 开源库&项目&工具
#### 1. [GABottleLoading](https://github.com/Ajian-studio/GABottleLoading)
Bezier storm（贝塞尔风暴）

![GABottleLoading](https://raw.githubusercontent.com/Ajian-studio/GABottleLoading/master/raw/bottleLoading_origin.gif)

#### 2. [remusic](https://github.com/aa112901/remusic)
仿网易云音乐安卓版客户端

![remusic](https://git.io/vMC6f)

#### 3. [PathAnimView](https://github.com/mcxtzhang/PathAnimView)
用于做Path动画的自定义View

![PathAnimView](https://github.com/mcxtzhang/PathAnimView/raw/master/gif/qianbihua.gif)

#### 4. [xLua](https://github.com/Tencent/xLua)
xLua is a hot-fix solution plugin for Unity3D, it supports android, ios, windows, osx, etc.

![xLua](https://github.com/Tencent/xLua/raw/master/Assets/XLua/Doc/xLua.png)

#### 5. [android-snowfall](https://github.com/JetradarMobile/android-snowfall)
Fully customizable implementation of "Snowfall View" on Android.

![android-snowfall](https://raw.githubusercontent.com/JetradarMobile/android-snowfall/master/art/hotellook-demo.gif)

## 联系方式
* Email：yanghui1986527#gmail.com
* QQ群: 529327615     
* 微信公众号:  sn0wdr1am    

![sn0wdr1am](https://static.dingtalk.com/media/lADOmAwFCs0BAs0BAg_258_258.jpg)
