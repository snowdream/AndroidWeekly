# Android开发技术周报 Issue#19

    声明：所有内容收集整理自网络。如有侵权，请联系删除。微信公众号上请点击“阅读原文”阅读完整版本。
    
## 业界新闻
![640.jpeg](http://upload-images.jianshu.io/upload_images/66954-d54b6266f0a8ba87.jpeg?imageMogr2/auto-orient/strip%7CimageView2/2/w/1240)
#### 1. [活动报名 | 走进阿里：Android 开发者沙龙](http://t.cn/RSzdbuW)
据官方数据Android 在全球已经激活 20 亿部设备，伴随着Android O Pre 2发布，Kotlin 成为 Android 官方编程语言， AI 时代的到来……这是 Android 开发者的狂欢还是梦魇，Android 开发的未来路在何方？Android 开发者又该做哪些技术储备和转型？
安卓绿色联盟携手阿里巴巴、华为共同举办"走进阿里：Android开发者沙龙"，于6月17日在杭州阿里巴巴西溪园区召开，邀请安卓开发者们欢聚一堂，共同交流探讨。

#### 2. [Android 免安装应用对所有开发者开放。立即开始构建免安装应用！](http://developers.googleblog.cn/2017/05/android.html)
今年早些时候，我们开始测试 Android 免安装应用，这是一种全新的 Android 应用，无须安装即可运行。感谢我们杰出的开发者社区，我们收到了大量反馈意见，帮助我们优化端到端的产品体验。

#### 3. [Android 出现了一款恶意软件，也能够勒索人](https://www.oschina.net/news/85216/malicious-software-on-android)
上次 WannaCry 勒索病毒席卷全球后，Windows XP 和未安装更新的 Windows 电脑遭遇了前所未有的安全问题。当然，这一事件有好有坏，好的一面也促使了更多的用户开始关注电子设备的安全问题。

现在，另一个安全问题出现在了全球手机操作系统占有率高达 86.1% 的 Android 上。

#### 4. [Tinker 1.7.11 发布，微信开源的 Android 热修复框架](https://www.oschina.net/news/85160/tinker-1-7-11)
Tinker 1.7.11 版本已发布，该版本是对前两天发布的 1.7.10 版本的修补。
1.7.11 更新内容：
* 修复1.7.10 版本替换 AndroidNClassloader 时可能产生 found duplicate classes warning f3e2f5d
* 修复自动 keep main dex pattern 中的问题，将 () 改为 (...) 492d6f
* Tinker 增加回退补丁的接口 855084

## Android开发
#### 1. [官方详细介绍Android Studio 3.0 Canary 1](http://t.cn/RSzBMsE)
为加快您的开发流，Android Studio 3.0 包含了三大主要功能：
* 一套全新的应用性能分析工具，用于快速诊断性能问题；
* 支持 Kotlin 编程语言；
* 加快大规模应用项目的 Gradle 构建速度。

#### 2. [教你如何自定义数字会滚动的TextView](http://t.cn/RSzrE4J)
NumberRunningTextView 是一个自带数字滚动动画的 TextView,通过使用 setContent(String str)方法，传入相应的金额数字字符串（如”1354.00”），或者数字的字符串（如200）,当页面初始化完成的时候，就可以看到数字滚动的效果，和支付宝中进入余额宝界面，显示余额滚动的效果类似。

#### 3. [【测试左移专栏】测试左移实践探讨 ——测试左移在腾讯地图SDK的实践](http://t.cn/RSzg29S)
我理解的"测试左移"，即将测试活动与开发活动结合更加紧密， 同步于开发活动甚至早于开发活动便开始的质量保障活动。业界已有关于测试前置的一些讨论, 因此本文也沿用测试前置的概念. 本文将讲解测试前置在腾讯地图SDK的实践情况。鉴于APP与SDK的不同形式，APP类产品在实践测试前置方法时需做适当调整。

#### 4. [Android下玩JNI的新老三种姿势](http://t.cn/RSzgdSD)
Android下玩JNI的新老三种姿势

#### 5. [BlockCanaryEx](https://github.com/seiginonakama/BlockCanaryEx/blob/master/README_ZH.md)
记录主线程中执行的所有方法和它们的执行时间，当app卡顿时，将所有耗时方法直接展示给开发者，节省开发者定位卡顿问题的时间。 此项目基于 BlockCanary。

#### 6. [Android截屏与WebView长图分享经验总结](http://mp.weixin.qq.com/s/wzx_ubix0ys50nxT_-JdMA)
最近在做新业务需求的同时，我们在 Android 上遇到了一些之前没有碰到过的问题，截屏分享、 WebView 生成长图以及长图在各个分享渠道分享时图片模糊甚至分享失败等问题，在这过程中踩了很多坑，到目前为止绝大部分的问题都还算是有了比较满意的解决方案。以下就从三个方面来总结一下过程中遇到的挑战和最后的解决方案。


## 开源库&项目&工具
#### 1. [Android 本地图片、视频选择器 Matisse](https://github.com/zhihu/Matisse)
Matisse 是知乎开源的一个漂亮的 Android 本地图片、视频选择器。其主要功能有：
*  选择包括 JPEG、PNG、GIF 格式的图片和 MPEG、MP4 格式的视频
*  支持自定义主题，包括两个内置的主题
*  不同的图片加载器
*  定义自定义过滤规则
*  在 Activities 和 Fragments 中使用良好
![Matisse](https://static.oschina.net/uploads/space/2017/0524/153616_onNA_2896879.png)

#### 2. [2017 春季最酷的 30 个 Android 库 【已翻译100%】](https://www.oschina.net/translate/30-new-android-libraries-released-in-the-spring-of-2017?lang=chs&page=1#)
![Spruce Android Animation Library ](https://static.oschina.net/uploads/space/2017/0523/111916_KknX_2896879.gif)

#### 3. [多页面切换场景统一解决方案 UltraViewPager ](https://github.com/alibaba/UltraViewPager)
UltraViewPager 是阿里开源的一个封装多种特性的 ViewPager ，主要是为多页面切换场景提供统一解决方案。
主要功能:
*  支持横向滑动／纵向滑动
*  支持一屏内显示多页
*  支持循环滚动
*  支持定时滚动，计时器使用 Handler 实现
*  支持设置 ViewPager 的最大宽高
*  setRatio 按比例显示 UltraviewPager
*  内置 indicator ，只需简单设置几个属性就可以完成展示，支持圆点和 Icon；
*  内置两种页面切换动效
![多页面切换场景统一解决方案 UltraViewPager](https://static.oschina.net/uploads/space/2017/0523/141236_iJ05_2896879.gif)

#### 4. [android-instant-apps](https://github.com/googlesamples/android-instant-apps)
Android Instant Apps 的例子项目

#### 5. [Kotlin第三方中文网站](https://www.kotlincn.net)
Kotlin第三方中文网站,资料可能比官网稍旧。

## 联系方式
* Email：yanghui1986527#gmail.com
* Github: https://github.com/snowdream
* Blog: http://snowdream.github.io/blog/
* 简书：http://www.jianshu.com/u/748f0f7e6432
* 云栖博客：https://yq.aliyun.com/u/snowdream86 
* QQ群: 529327615     
* 微信公众号:  sn0wdr1am    

![sn0wdr1am](https://static.dingtalk.com/media/lADOmAwFCs0BAs0BAg_258_258.jpg)
