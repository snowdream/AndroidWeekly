# Android开发技术周报 Issue#13

    声明：所有内容收集整理自网络。如有侵权，请联系删除。微信公众号上请点击“阅读原文”阅读完整版本。
    
## 业界新闻
#### 1. [Android Things Developer Preview 3发布](http://t.cn/RXUR4uE)
4 月 6 日，我们发布了 Android Things Developer Preview 3 (DP3)，为该平台带来了一些新功能并修复了若干问题。我们承诺为通过我们平台构建物联网 (IoT) 产品的开发者提供定期更新，而此预览版是践行此承诺的一部分。Android 开发者可使用 Android API 和 Google 服务快速构建智能设备，同时依靠 Google 直接提供的更新始终确保安全性。模块化系统 (SoM) 架构支持使用开发板进行原型开发，然后将原型开发扩展到大规模量产，而与此同时，您仍可继续使用 Google 的 Board Support Package (BSP)。 

#### 2. [Android Studio 2.4 Preview 5 发布](https://www.oschina.net/news/83712/android-studio-2-4-preview5)
Android Studio 2.4 Preview 5 发布了。

Fixes  
* Android Studio 2.4 Preview 5 包含了 IntelliJ 2017.1 的更新。 这是 JetBrains 最新的稳定版本，可能是 Android Studio 2.4 中最后一个主要的IntelliJ更新。
*  我们将继续提升版本质量

## Android开发
#### 1. [Android GC 原理探究](http://t.cn/RXU8NB5)
想写一篇关于android GC的想法来源于追查一个魅族手机图片滑动卡顿问题，由于不断的GC导致的丢帧卡顿的问题让我们想了很多方案去解决，所以就打算详细的看看内存分配和GC的原理，为什么会不断的GC，GC ALLOC和GC COCURRENT有什么区别，能不能想办法扩大堆内存减少GC的频次等等。

#### 2. [介绍Android原生开发工具包r14](http://t.cn/RXU8rFk)
现在，可以下载最新版本 Android 原生开发工具包 (NDK)——Android NDK r14。也可以通过 Android Studio 在 SDK 管理器中下载此版本：
https://developer.android.google.cn/ndk/downloads/index.html

#### 3. [LQRAudioRecord](http://www.jianshu.com/p/27cf4b616f9b)
本库集成录音与播音功能，使用简单方便，让IM集成语音不再是难题。

#### 4. [浅谈对于mp3文件中VBR对比CBR的一些基本差异](https://mp.weixin.qq.com/s/TgaTCBl3tlFqvPPPq-hMWA)
从比特率编码方式的角度来看，目前其中一种最常见的音频文件格式MP3，可以再分为两种类型：一种是恒定比特率CBR（Constant Bit-Rate），这种类型的mp3每一帧的比特率都是恒定唯一的；另外一种就是可变比特率VBR（Variable Bit-Rate），这种类型就跟CBR相反，每一帧的比特率是不固定的，帧与帧之间的比特率可能一样也可能不一样。由于存在这样两种类型，播放mp3文件时需要做的一些工作，比如获取音频信息和播放进度控制，就需要分开处理。

## 开源库&项目&工具
#### 1. [从浏览器控制和管理 Android 设备 STF](https://www.oschina.net/p/stf?fromerr=TaH81f5F)
STF（or Smartphone Test Farm）是一个 Web 应用程序，用于从舒适的浏览器远程调试智能手机，智能手表和其他小工具。

![从浏览器控制和管理 Android 设备 STF](https://static.oschina.net/uploads/space/2017/0410/163239_Jx25_2720166.jpg) 
具有以下功能

* 支持 Android 2.3 ~ 5.1：包括 Preview M, Wear, FireOS

* 键盘和鼠标输入：以及多点触控，即使在 iOS 的 Safari 浏览器中

* 复制和粘贴：在设备中操作

* 获取屏幕截图并调整大小

* 拖放 APK 文件：一步安装和启动应用程序

* 在任意已安装的浏览器中打开 URL

* 显示实时过滤的日志

* 不用离开浏览器运行 Shell 命令

* 使用 Android Studio，Chrome 调试工具进行远程调试

* 以及更多：反向端口转发，设备旋转……

#### 2. [SlidingRootNav](https://github.com/yarolegovich/SlidingRootNav)
DrawerLayout-like ViewGroup, where a "drawer" is hidden under the content view, which can be shifted to make the drawer visible.
![SlidingRootNav](https://github.com/yarolegovich/SlidingRootNav/blob/master/art/sample.gif?raw=true)

#### 3. [GSYVideoPlayer](https://github.com/CarGuo/GSYVideoPlayer)
视频播放器（IJKplayer），HTTPS支持，支持弹幕，支持基本的拖动，声音、亮度调节，支持边播边缓存，支持视频本身自带rotation的旋转（90,270之类），重力旋转与手动旋转的同步支持，支持列表播放 ，直接添加控件为封面，列表全屏动画，视频加载速度，列表小窗口支持拖动，5.0的过场效果，调整比例，多分辨率切换，支持切换播放器，进度条小窗口预览，其他一些小动画效果。简书: http://www.jianshu.com/p/9fe377dd9750

#### 4. [Git常用终端命令](http://www.jianshu.com/p/87ab8acf4b87)
Git常用终端命令

## 联系方式
* Email：yanghui1986527#gmail.com
* Github: https://github.com/snowdream
* Blog: http://snowdream.github.io/blog/
* 简书：http://www.jianshu.com/u/748f0f7e6432
* 云栖博客：https://yq.aliyun.com/u/snowdream86 
* QQ群: 529327615     
* 微信公众号:  sn0wdr1am    

![sn0wdr1am](https://static.dingtalk.com/media/lADOmAwFCs0BAs0BAg_258_258.jpg)
