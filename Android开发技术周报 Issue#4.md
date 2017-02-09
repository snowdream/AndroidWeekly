# Android开发技术周报 Issue#4

    声明：所有内容收集整理自网络。如有侵权，请联系删除。
  
## 业界新闻
#### 1. [谷歌I/O 2017大会日期地址公布：5月17日举办](http://www.ithome.com/html/android/290578.htm)
根据官方推特分析，Google I/O 2017开发者大会将于5月17日至19日，于加州山景城的露天剧场举办。谷歌I/O官网上目前还没有更新有关2017年大会的消息，应该将在不久后进行更新。

#### 2. [OPPO首超华为，成国内智能机年度出货冠军！小米暴降36%](http://t.cn/RJZOfIf)
国际数据公司（IDC）最新发布的手机季度跟踪报告显示，2016年第四季度，中国智能手机市场出货量同比增长18.7%。OPPO、华为、Vivo成为中国智能手机市场出货量前三，其中OPPO的增长量达到了109.2%。

#### 3. [网易或在中国运营谷歌应用商店，已经开始谈判](https://view.inews.qq.com/a/TEC2017020700552607)
据外媒最新消息，谷歌正在和中国互联网公司网易进行接触，谷歌可能通过网易在中国经营Play商店。网易和谷歌目前正在就此事进行磋商，但是双方是否会达成合作尚未可知。谷歌母公司Alphabet的董事长施密特此前曾经表示，在中国市场，谷歌需要寻找到一个商业伙伴来开展自身的一些业务，尤其是负责和政府监管部门之间的沟通。

## Android开发
#### 1. [Android硬件加速原理与实现简介](http://tech.meituan.com/hardware-accelerate.html)
在手机客户端尤其是Android应用的开发过程中，我们经常会接触到“硬件加速”这个词。由于操作系统对底层软硬件封装非常完善，上层软件开发者往往对硬件加速的底层原理了解很少，也不清楚了解底层原理的意义，因此常会有一些误解，如硬件加速是不是通过特殊算法实现页面渲染加速，或是通过硬件提高CPU/GPU运算速率实现渲染加速。

#### 2. [聊聊clean code](http://tech.meituan.com/clean-code.html)
clean code，顾名思义就是整洁的代码，或者说清晰、漂亮的代码，相信大多数工程师都希望自己能写出这样的代码。也许这是个千人千面的话题，每个工程师都有自己的理解。比如我，从一个天天被骂代码写得烂的人，逐渐学习成长，到现在也能写的出“人模人样”的代码来了。这期间算是积累了一点经验心得，想和大家分享，抛砖引玉。本文主要针对面向对象编程的clean code来阐述，面向过程代码的思路会比较不同，不在本文的讨论范畴。

#### 3. [Android 内存泄漏分析心得](http://t.cn/RMdiwom)
对于C++来说，内存泄漏就是new出来的对象没有delete，俗称野指针；对于Java来说，就是new出来的Object 放在Heap上无法被GC回收；本文通过QQ和Qzone中内存泄漏实例来讲android中内存泄漏分析解法和编写代码应注意的事项。

#### 4. [Android动态库压缩壳的实现](http://t.cn/RMdJ8T9)
说起壳可能有的同学并不太了解，简单的说，计算机软件领域所说的壳实际上是一种软件加密技术。与自然界中的壳类似，花生用壳保护种子，乌龟用壳保护自己的身体，而我们写的程序为了在一定程度上防止被逆向分析，也可以给它加壳。壳主要分为两大类：加密壳和压缩壳，加密壳侧重于防止软件被篡改，而压缩壳则侧重于减小软件体积。其实，在Windows上已经有许多壳了，但Android（或者可以说Linux）上的壳相对而言就少了一些。本文就主要讲讲Android动态库（so文件）压缩壳要如何实现。

#### 5. [Espresso浅析和使用](http://t.cn/RMdJ9oB)
Espresso是一个Google官方提供的Android应用UI自动化测试框架。Google希望，当Android的开发者利用Espresso写完测试用例后，能一边看着测试用例自动执行，一边享受一杯香醇Espresso(浓咖啡)。Espress有3个特点：1.第一个收录在Android Testing Supporting Library底下的测试框架； 2.模拟用户的操作；3.自动等待，直到UI线程Idle，才会执行测试代码。接下来，将从配置、写用例、运行一步步介绍Espresso的使用。

#### 6. [通过ContentProvider多进程共享SharedPreferences数据](http://www.jianshu.com/p/bdebf741221e)
开发一个多进程应用的时候，我们往往无法避免在多个进程之间共享数据。 多进程共享数据的方法有很多种，在Android中常用的有：SharedPreferences(多进程模式)、广播、Socket、ContentProvider、Messenger、AIDL等。这些方法适用于不同的使用场景，又有各自的局限性。本文即将介绍的是通过ContentProvider，结合SharedPreferences(以下简称SP)实现的进程间共享设置项的功能。这种方式主要适用于以下场景：在一个进程中进行一些设置，而需要在另一个进程实时读取设置，并根据这些设置来执行功能。

#### 7. [看AspectJ在Android中的强势插入](http://t.cn/RMdIelN)
AOP是Aspect Oriented Programming的缩写，即『面向切面编程』。它和我们平时接触到的OOP都是编程的不同思想，OOP，即『面向对象编程』，它提倡的是将功能模块化，对象化，而AOP的思想，则不太一样，它提倡的是针对同一类问题的统一处理，当然，我们在实际编程过程中，不可能单纯的安装AOP或者OOP的思想来编程，很多时候，可能会混合多种编程思想，大家也不必要纠结该使用哪种思想，取百家之长，才是正道。

#### 8. [Android工程gradle详解](https://gold.xitu.io/post/58945a8b570c3500623081f0)
当工程中有许多module的时候，分开管理编译版本，minsdk将会是一件很麻烦的事，因为一个library的改动，可能会影响到其他module。这时我们就需要对所有的版本进行统一的管理，这个时候就该gradle上场了。本文详细介绍了gradle的操作方法。

#### 9. [Android 6.0 SSL通信](http://www.jianshu.com/p/fefeb1b310f1)
在Android平台上使用SSL，第一步就是要生成证书。因为JDK自带的keytool工具默认生成的密钥库是JKS类型的，而Android客户端只支持BKS类型的密钥库，所以必须先扩展keytool工具使其生成BKS密钥库。要扩展，则需要下载BouncyCastle库。本文给出了生成证书的方法并且提供了具体的实现代码。

#### 10. [安卓逆向系列教程](http://blog.csdn.net/wizardforcel/article/details/54730253)
从事逆向工作的人并不是很多，但反编译过App的开发者应该不在少数。本文作者写了一个系列的文章专门介绍Android逆向的知识，学习逆向知识不仅仅是破解别人的App，更重要的是对于我们进行安防有一定的帮助。

#### 11. [Android打包之多版本、多环境、多渠道](http://www.jianshu.com/p/872dc6f89cb4)
Android打包之多版本、多环境、多渠道

## 开源库&项目&工具
#### 1. [lottie-android](https://github.com/airbnb/lottie-android)
一个神奇的动画开源项目，动画效果非常赞，项目来自独角兽公司Airbnb。

![lottie-android](https://raw.githubusercontent.com/airbnb/lottie-android/master/gifs/Example2.gif)

#### 2. [Android-SplashView](https://github.com/jkyeo/Android-SplashView)
该项目可以帮助开发者通过简单的几行代码管理闪屏页或广告页。

#### 3. [walle](https://github.com/Meituan-Dianping/walle)
Android Signature V2 Scheme签名下的新一代渠道包打包神器。walle通过在Apk中的APK Signature Block区块添加自定义的渠道信息来生成渠道包，从而提高了渠道包生成效率，可以作为单机工具来使用，也可以部署在HTTP服务器上来实时处理渠道包Apk的升级网络请求。

#### 4. [Toasty](https://github.com/GrenderG/Toasty)
The usual Toast, but with steroids 💪
![Toasty](https://raw.githubusercontent.com/GrenderG/Toasty/master/art/scr2.png)


## 联系方式
* Email：yanghui1986527#gmail.com
* QQ群: 529327615     
* 微信公众号:  sn0wdr1am    

![sn0wdr1am](https://static.dingtalk.com/media/lADOmAwFCs0BAs0BAg_258_258.jpg)
