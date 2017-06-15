# Android开发技术周报 Issue#22

    声明：所有内容收集整理自网络。如有侵权，请联系删除。微信公众号上请点击“阅读原文”阅读完整版本。
    
## 业界新闻
#### 1. [Android O API 已发布最终版本](http://t.cn/RSFEoxM)
在上个月举行的 Google I/O 大会上，我们宣布了 Android O 的第二个开发者预览版，同时介绍了 Fluid Experiences 和 Vitals 等重要主题，并且重点介绍了我们利用 Treble 项目实现库模块化方面的工作进展。

#### 2. [谷歌官方确认：Android O 的版本号为 8.0](https://www.oschina.net/news/85659/android-8-0-beta3)
今天，谷歌为参与 Android Beta 的用户推送了全新的 Android O 系统，也就是第三个开发者预览版。

#### 3. [大势所趋，WebAssembly 将统一浏览器编译格式](https://www.oschina.net/news/85644/webkit-now-complete-support-webassembly)
被 Safari、App Store 以及许多其他 OS X、iOS 和 Linux 应用所广泛使用的开源 Web 浏览器引擎 WebKit ，如今有了完整的 WebAssembly 部署能力。就在上周，Google Chrome 也宣布将停止支持 PNaCl ，拥抱 WebAssembly ，并表示因为考虑到跨浏览器支持乃是大势所趋，今后主要依靠 WebAssembly 构建原生代码。

## Android开发
#### 1. [微信移动端数据库组件WCDB系列（三） — WINQ原理篇](http://t.cn/RSFnLnD)
高效、完整、易用是WCDB的基本原则。前几篇文章分享了WCDB的基本用法和修复工具，接下来将更深入地聊聊WCDB在易用性上的思考和实践。

#### 2. [微店 Android 插件化实践](http://t.cn/RS1GF0k)
随着微店业务的发展，App不可避免的也遇到了65535的大坑。除此之外，业务模块增多，代码量增大所带来的问题也逐渐显现出来。模块耦合度高、协作开发困难、编译时间过长等问题严重影响了开发进程。在预研了多种方案以后，插件化似乎是解决这些问题比较好的一个方向。虽然业界有很多优秀的开源插件化框架， 但预研后发现在使用上对我们会有一定的局限。要么追求低侵入性而Hook大量系统底层代码稳定性不敢保证，要么有很高的侵入性不满足微店定制化的需求。技术要很好地服务业务，我们想在稳定性和低侵入性上寻找一个平衡……

#### 3. [开发者大杀器 —— 刨根问底，揪出 Android App 耗电的元凶代码](http://www.jianshu.com/p/27ba2759b221)
这是一篇讲述应用耗电的文章，围绕 Android 电量采集机制及第二代 Battery Historian 分析工具讲述。文从数据采集、导出、环境搭建、解读报告的角度出发，从细节讲解整个流程。和大谈概念的文章不同，这里将进行实际操作及分析。

#### 4. [QQ会员基于hybrid的高质量H5架构实践](http://t.cn/RSFuFMM)
本文主要介绍QQ会员的前端开发团队在手Q的hybrid模式下对H5页面的性能优化、组件化和持续集成方面的实践。

#### 5. [WebView缓存原理分析和应用](http://unclechen.github.io/2017/05/13/WebView缓存原理分析和应用/)
现在的App开发，或多或少都会用到Hybrid模式，到了WebView这边，经常会加载一些js文件（例如和WebView用来Native通信的bridge.js），而这些js文件不会经常发生变化，所以我们希望js在WebView里面加载一次之后，如果js没有发生变化，下次就不用再发起网络请求去加载，从而减少流量和资源的占用。那么有什么方式可以达到这个目的呢？先得从WebView的缓存原理入手。

#### 6. [Android卡顿检测方案](http://blog.coderclock.com/2017/06/04/android/AndroidPerformanceTools-BlockLooper/)
应用的流畅度最直接的影响了App的用户体验，轻微的卡顿有时导致用户的界面操作需要等待一两秒钟才能生效，严重的卡顿则导致系统直接弹出ANR的提示窗口，让用户选择要继续等待还是关闭应用。

#### 7. [Android 多状态加载布局的开发 Tips](http://gudong.name/2017/04/26/loading_layout_practice.html)
对应到开发中，我们通常会开发一个对应的自定义 layout 用于根据页面不同的状态来显示不同的提示 view。


## 专题栏目 － HttpResponseCache
#### 1. [如何高效的使用Okhttp](https://xiequan.info/如何高效的使用okhttp/?utm_source=tuicool&utm_medium=referral)
OkHttp是一个在开发可汗学院Android APP过程中非常重要的依赖库。它的默认的配置为我们提供了非常重要实用功能，下面一些步骤我们可以让Okhttp提供更多功能使用灵活和自省能力。

#### 2. [Android中HTTP相关的API](http://droidyue.com/blog/2015/05/30/android-http-clients/index.html)
Android中大多数应用都会发送和接受HTTP请求，在Android API中主要由两个HTTP请求的相关类，一个是HttpURLConnection，另一个是Apache HTTP Client。这两个类实现的HTTP请求都支持HTTPS协议，基于流的上传和下载，可配置超时时间，IPv6和连接池。

#### 3. [ HttpResponseCache的使用 缓存 cache](http://blog.csdn.net/yhqbsand/article/details/8596975)
之前我们在软件开发中，cache都是自己来写，不管是图片缓存还是其他从网络获取的数据，有了HttpResponseCache，它帮助我们可以很好的解决cache这个问题（我现在感觉他只适合cache一些小的数据，如果大量的图片cache还是自己缓存到SD卡上面去比较好）。

#### 4. [HttpResponseCache原理分析](http://qianzui.github.io/blog/2015-03-29-httpresponsecache-source-code-analysis/)
从Android4.0(API 14)开始，SDK源码中新增了一个类:android.net.http.HttpResponseCache.使用这个类可以很方便的对HTTP和HTTPS请求实现cache，所有的缓存逻辑再也不用自己写了，只要你使用HttpURLConnection或者HttpsURLConnection作为默认的网络请求库(也是Google官方建议使用的)，底层默认帮你实现的缓存的管理，不支持HttpClient。


## 开源库&项目&工具
#### 1. [Graywater](https://github.com/tumblr/graywater)
An Android library for decomposing RecyclerView layouts to improve scroll performance.

#### 2. [MagicIndicator](https://github.com/hackware1993/MagicIndicator)
A powerful, customizable and extensible ViewPager indicator framework. As the best alternative of ViewPagerIndicator, TabLayout and PagerSlidingTabStrip —— 强大、可定制、易扩展的 ViewPager 指示器框架。是ViewPagerIndicator、TabLayout、PagerSlidingTabStrip的最佳替代品。支持角标，更支持在非ViewPager场景下使用（使用hide()、show()切换Fragment或使用setVisibility切换FrameLayout里的View等）

#### 3. [ViewTooltip](https://github.com/florent37/ViewTooltip)
A fluent tooltip for Android

#### 4. [SwiftKotlin](https://github.com/angelolloqui/SwiftKotlin)
A tool to convert Swift code to Kotlin.

#### 5. [SmartTabLayout](https://github.com/ogaclejapan/SmartTabLayout)
A custom ViewPager title strip which gives continuous feedback to the user when scrolling

#### 6. [ShadowImageView](https://github.com/yingLanNull/ShadowImageView)
🔥可以根据图片内容变阴影颜色，更加细腻的阴影效果 It can change color according to the picture, more delicate shadow effect

#### 7. [easypermissions](https://github.com/googlesamples/easypermissions)
Simplify Android M system permissions

#### 8. [AndroidPerformanceTools](https://github.com/D-clock/AndroidPerformanceTools)
本项目用于整理安卓性能监测方案，如果你有不错的方案推荐，欢迎给我提个Issue！

#### 9. [Aria](https://github.com/AriaLyy/Aria)
一个简单易用，稳当高效的下载框架。

## 联系方式
* Email：yanghui1986527#gmail.com
* Github: https://github.com/snowdream
* Blog: http://snowdream.github.io/blog/
* 简书：http://www.jianshu.com/u/748f0f7e6432
* 云栖博客：https://yq.aliyun.com/u/snowdream86 
* QQ群: 529327615     
* 微信公众号:  sn0wdr1am    

![sn0wdr1am](https://static.dingtalk.com/media/lADOmAwFCs0BAs0BAg_258_258.jpg)
