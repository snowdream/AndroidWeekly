# Android开发技术周报 Issue#7

    声明：所有内容收集整理自网络。如有侵权，请联系删除。

## 业界新闻
#### 1. [Kotlin 1.1 正式版来了，基于 JVM 的编程语言](https://www.oschina.net/news/82431/kotlin-1-1)
开发团队宣布，Kotlin 1.1 正式发布。 这是一个很大的进步，使 Kotlin 能在许多新的场景中使用。

Kotlin 的愿景是在现代应用程序的所有组件中使用单一的表达式，高性能的强类型语言。 Kotlin 1.1 为实现这一目标迈出了两大步。

#### 2. [React Native 0.42.0 正式发布，大量修复和改进](https://www.oschina.net/news/82455/react-native-0-42-0)
重大更新：

Android

* windowSoftInputMode for new apps：使用 react-native init 创建的所有新应用程序都将具有 windowSoftInputMode：adjustResize 而不是 adjustUnspecified，这已设为默认值。 这种改变使得 Android 上的键盘处理变得自动化，并且不需要任何 Javascript 解决方案。

* (Re)move JSBundleLoader.getSourceUrl()

* 移除 RecyclerViewBackedScrollView：RecyclerViewBackedScrollView 是很久以前添加的，为了解决数据添加错误，但现在该问题已经直接在开源和内部的 ScrollView（ReactScrollView.java）中修复。

Android&iOS

* 改进变换属性的验证：这个提交改进了在 Javascript 侧完成的变换对象的验证，并且使其更严格。在此更改中，确保JS验证与本机验证相同或更严格，以确保跨平台获得一致的错误。

## Android开发
#### 1. [GDE专栏 | Android Things开发环境搭建](http://t.cn/RiMpKzb)
物联网 (IoT) 的应用开发，离不开跟开发板打交道，我们需要配置好开发板的各种环境，最后才能用 Android Studio 进行应用开发。

我们今天就以 Raspberry Pi 3 为例，一起来搭建 Android Things 的开发环境。

#### 2. [内存泄漏全解析](http://t.cn/RiMpgMY)
对于 C++ 来说，内存泄漏就是new出来的对象没有 delete，俗称野指针；而对于 java 来说，就是 new 出来的 Object 放在 Heap 上无法被GC回收；而这里就把我之前的一篇内存泄漏的总结翻新，做一个更加全面规范的讲解，希望能帮到各位。

#### 3. [Google VR for Android 敲门](http://www.jianshu.com/p/7867fe980fb4)
虚拟现实（Virtual Reality）技术是一种可以创建和体验虚拟世界的计算机仿真系统，最近几年虚拟现实概念很火，技术上也有很多突破。Google、苹果等顶级互联网公司都进行了大手笔的投入。本文是一篇介绍如何在Android手机上运行、开发VR程序的基础教程。

#### 4. [深度了解Android 7.0 ，你准备好了吗？](http://mp.weixin.qq.com/s/8Nouh0ZZklqjxfachhoA-g)
2016年8月22日，谷歌正式推送Android 7.0 Nougat（牛轧糖）正式版，他们还会三个月一次推送开发版，而曝光的消息看，第一个开发版就是Android 7.1，Android N主要新增了以下的新特性和优化。Android N 增加了许多新的notifications API，进行了重新的设计，引入了新的风格。1.模板更新：开发者将能够充分利用新模板，只需进行少量的代码调整。2.消息样式自定义：可以自定义更多与使用MessageStyle类的通知相关的用户界面标签。可以配置消息、会话标题和内容视图。

#### 5. [蘑菇街Android热修复探索之路](http://mp.weixin.qq.com/s/GuzbU1M1LY1VKmN7PyVbHQ)
文章包含三部分：1.业界各方案简介；2.蘑菇街HotFix:Q-Zone篇，介绍ART Runtime对Q-Zone方案的限制；3.蘑菇街HotFix:Aceso篇，介绍Aceso在InstantRun方案上的各种优化。业界各方案简介 在Dalvik时代，只有Dexposed跟Q-Zone两家的方案，进入ART时代后各种Android热修复方案如雨后春笋般冒出来。

## 开源库&项目&工具
#### 1. [MaterialDrawer 5.8.2 发布，Android 侧滑显示控件](https://www.oschina.net/news/82351/materialdrawer-5-8-2)
MaterialDrawer 5.8.2 发布了，MaterialDrawer 是一个类似 Google 官方 NavigationView 侧滑显示控件, 能够实现跟 NavigationView 一样的效果, 同时还支持自定义效果, 自由度非常高。

#### 2. [gradle-completion](https://github.com/eriwen/gradle-completion)
Gradle tab completion for bash and zsh
![gradle-completion](https://raw.githubusercontent.com/eriwen/gradle-completion/master/gradle-completion-short.gif)

#### 3. [gradle-tips](https://github.com/shekhargulati/gradle-tips)
In this document, I will list down tips that I have learnt over last year or so.

#### 4. [开源许可协议了解这些就够了](http://t.cn/RiM0UCJ)
现今存在的开源协议很多，可以在（http://www.opensource.org/licenses/alphabetical ）详细查看。我们最常用到的开源协议有6种，这些都是OSI 批准的协议，也是绝大多数公司会用到的协议。

#### 5. [Fragmentation](https://github.com/YoKeyword/Fragmentation)
A powerful library that manage Fragment for Android!

#### 6. [AndroidIconAnimator](https://github.com/romannurik/AndroidIconAnimator)
A web-based tool that lets you design icon animations and other animated vector art for Android. Exports to Animated Vector Drawable format for Android.

#### 7. [geometric-progress-view](https://github.com/vbohush/geometric-progress-view)
Customizable progress indicator in the form of 2D geometric shapes

![geometric-progress-view](https://github.com/vbohush/geometric-progress-view/raw/master/screenshot/screenshot.gif)

## 联系方式
* Email：yanghui1986527#gmail.com
* Github: https://github.com/snowdream
* Blog: http://snowdream.github.io/blog/
* 简书：http://www.jianshu.com/u/748f0f7e6432
* 云栖博客：https://yq.aliyun.com/u/snowdream86 
* QQ群: 529327615     
* 微信公众号:  sn0wdr1am    

![sn0wdr1am](https://static.dingtalk.com/media/lADOmAwFCs0BAs0BAg_258_258.jpg)
