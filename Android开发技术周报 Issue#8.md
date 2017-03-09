# Android开发技术周报 Issue#8

    声明：所有内容收集整理自网络。如有侵权，请联系删除。

## 业界新闻
#### 1. [Android Studio 2.3 正式版发布](https://www.oschina.net/news/82493/android-studio-2-3-final)
Android Studio 2.3 正式版发布了，该版本包含一些新特性，包括对 WebP 支持的更新；ConstraintLayout 库支持更新和布局编辑器的部件面板。提供一个新的 App Link 助手可以帮助你在应用中构建 URI 的统一视图。新的运行按钮提供更直观和可靠的立即运行体验。最后是 Android 模拟器的测试，支持文本的复制和粘贴。详细介绍请看官方发行说明。


## Android开发
#### 1. [从源码出发浅析Android TV的焦点移动原理-上篇](http://t.cn/RijmFaS)
#### 2. [从源码出发浅析Android TV的焦点移动原理-下篇](http://t.cn/RijuZQG)
相对于手机上用手指点击屏幕产生的Click事件， 在使用Android TV的过程中，遥控器是一个主流的操作工具，通过点击遥控器的方向键来控制焦点的移动。当焦点移动到目标控件上之后，按下遥控器的确定键，才会触发一个Click事件，进而去做下一步的处理。焦点的移动如下图所示。

#### 3. [RecyclerView 实现滑动删除和拖拽功能](http://t.cn/RijuV2v)
从Android 5.0开始，谷歌推出了新的控件RecyclerView，相对于早它之前的ListView，优点多多，功能强大，也给我们的开发着提供了极大的便利，今天自己学习一下RecyclerView轻松实现滑动删除及拖拽的效果。

#### 4. [Android性能优化（一）之启动加速35%](http://www.jianshu.com/p/f5514b1a826c)
从应用的启动优化开始，根据实际案例，打造闪电般的App启动速度。

#### 5. [Android 7.0应用冷启动流程分析](http://blog.csdn.net/dd864140130/article/details/60466394)
最近在为自己Moto G定制Rom,顺便重新读了一遍Android 7.0的相关源码,特此记录当做笔记.

#### 6. [Android LayoutInflater源码解析](http://allenfeng.com/2017/02/24/how-android-layout-inflater-work/)
大家对LayoutInflater一定不陌生，LayoutInflater是一个用于将xml布局文件加载为View或者ViewGroup对象的工具，我们可以称之为布局加载器。在Fragment的onCreateView方法、ListView Adapter的getView方法等许多地方都可以见到它的身影。本文详细介绍了LayoutInflater的用法以及加载布局的工作原理。

#### 7. [Android应用安全风险与防范](https://zhuanlan.zhihu.com/p/25571814?hmsr=toutiao.io)
Android开发除了部分功能采用C/C++编码外，其余主要都是采用Java进行编码开发功能。Java应用非常容易被反编译，Android自然也不例外。只要利用apktool等类似的反编译工具，就可以通过安装包获取源代码。Google为了保护开发者的知识产权，为Android提供了ProGuard混淆方案，以增加反编译后源码阅读，但对于Android开发老司机和逆向工程师来说，解读还原出源代码只是时间问题。

#### 8. [Android架构那些事之第三方库的隔离](http://www.jianshu.com/p/d959250e0624)
我们都知道一个好的架构会使我们的开发变得事半功倍。
设计架构的目的在于使我们的客户端易于扩展、方便单元测试、可复用。
做到使模块之间低耦合，模块内部高内聚。

#### 9. [微信tinker快速集成](http://www.jianshu.com/p/e71f73c83045)
微信tinker快速集成

## 开源库&项目&工具
#### 1. [vlayout](https://github.com/alibaba/vlayout)
vlayout是手机天猫Android版内广泛使用的一个基础UI框架项目。提供了一个用于RecyclerView的自定义的LayoutManger，可以实现不同布局格式的混排，目标是支撑客户端native页面的快速开发。它也是Tangram框架的基础模块。

#### 2. [AndroidSkinAnimator](https://github.com/wutongke/AndroidSkinAnimator)
皮肤切换动画，支持全局View animation everywhere

![AndroidSkinAnimator](https://raw.githubusercontent.com/wutongke/AndroidSkinAnimator/master/gif/5.gif)

#### 3. [CameraKit-Android](https://github.com/flurgle/CameraKit-Android)
CameraKit is an extraordinarily easy to use utility to work with the infamous Android Camera and Camera2 APIs. Built by Dylan McIntyre.

#### 4. [Android-CleanArchitecture](https://github.com/android10/Android-CleanArchitecture)
This is a sample app that is part of a series of blog posts I have written about how to architect an android application using Uncle Bob's clean architecture approach.

## 联系方式
* Email：yanghui1986527#gmail.com
* Github: https://github.com/snowdream
* Blog: http://snowdream.github.io/blog/
* 简书：http://www.jianshu.com/u/748f0f7e6432
* 云栖博客：https://yq.aliyun.com/u/snowdream86 
* QQ群: 529327615     
* 微信公众号:  sn0wdr1am    

![sn0wdr1am](https://static.dingtalk.com/media/lADOmAwFCs0BAs0BAg_258_258.jpg)
