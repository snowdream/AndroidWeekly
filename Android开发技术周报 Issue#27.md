# Android开发技术周报 Issue#27

    声明：所有内容收集整理自网络。如有侵权，请联系删除。微信公众号上请点击“阅读原文”阅读完整版本。
    
## 业界新闻
#### 1. [Android 8.0 正式版要来了，预计 8 月初推出](https://www.oschina.net/news/86939/android-o-release-date)
最新的消息，据 PhoneArena 报道，Android 8.0 正式版定于2017年8月中上旬推出。本月底，最后一个开发者预览版（Developer Preview 4）就会放出，从而无限接近正式形态。

#### 2. [真的来了！工信部将成立安卓统一推送联盟](https://www.oschina.net/news/86943/android-messaging-standard)
上个月，工信部旗下泰尔实验室发布消息称，将在国内联合多家厂商制定安卓统一推送服务（Unified Push Service，简称UPS）技术标准，旨在为国内的消息推送服务建立统一的标准，为终端用户提供更好的手机使用体验，为应用开发者更好解决消息推送需求，目前该标准已经进入厂商招募阶段。

## Android开发
#### 1. [有了libco，异步化都成了小case！](http://t.cn/RKBRZy0)
工作后一直在做c++后台服务开发，框架基本都是多进程多线程的模型，也基本能解决绝大部分问题。不同的应用场景下，可以通过同步或者异步的方式来满足业务或者性能的要求。

#### 2. [Android远程调试的探索与实现](http://t.cn/RKBQKA4)
能否开发一种工具，既不需要用户深度配合也不需要提前埋点就能方便、快速地定位线上问题？

#### 3. [页面结构化在 Android 上的尝试](http://t.cn/RKBQ8iN)
MVP开发模式可以帮助项目结构解耦，但其庞大的方法数增加，较为笨重设计对于手Q项目并不很适合。参考之前Web开发经验，提出以页面结构化的解耦方式组织代码。下面讲讲Lego在Android上一次小小尝试。

#### 4. [Android 视图高度和阴影的那点事儿](http://yifeng.studio/2017/02/26/android-elevation-and-shadow/)
Material Design 规范针对 UI 元素提出了“高度”这一概念，使过去流行于拟物化设计中的阴影效果，在扁平化设计中消失了很久之后，再次显现。不过，虽然视图高度更多的是以阴影的形式直观地表现在界面中，但更多地是强调一个元素相对重要性的问题。在三维空间中，拥有更高高度的 UI 元素，显然对于用户来讲，相比于其他元素，更加凸显其重要性，更加希望被用户注意到，甚至被频繁操作，这也是设计人员最想表达的初衷。

#### 5. [在Android中实现阴影效果](http://www.yiqivr.com/2015/03/03/在Android中实现阴影效果/)
在Android L推出后，Google提出了全新的设计语言：材质设计。其中很重要的一点就是阴影效果的使用，你可以为每一个View设置一个elevation值，相当于除了x、y之外的z值，z值决定了阴影的大小，z值越大表示阴影越大。z值包含两个成分：elevation和translation。elevation是一个静态的成分，translation使用了动画：Z = elevation + translationZ。

#### 6. [Kotlin 101](http://www.slatekit.com/kotlin101.html)
This is a introduction to Kotlin which covers the language features in a concise, reference style approach. For more in-depth documentation please refer to the resources below.

#### 7. [Kotlin 语言入门宝典 | Android 开发者 FAQ Vol.5](http://t.cn/RKBQUL0)
随着 Kotlin 的快速崛起，我们注意到越来越多的开发者开始关注这个新兴的语言。本期《Googel Play 开发者 FAQ》，我们特别推出了 Kotlin 语言专题，希望这些内容有助于您更好地了解 Kotlin 语言的特性和发展现状，并尝试使用 Kotlin 语言进行 Android 开发。


#### 8. [Gradle详解：使用 Gradle 对应用进行个性化定制](http://t.cn/RKB8yNK)
本篇文章主要根据实际开发中遇到的需求，讲解使用 Gradle 对应用的不同版本进行个性化定制。

#### 9. [Kotlin中的单例模式](http://droidyue.com/blog/2017/07/17/singleton-in-kotlin/)
在编程中，我们都应该接触到设计模式，无论是从时间总结，亦或者是从书上习得后尝试使用。这其中单例模式，是我们编程过程中很常见，也很简单的一种设计模式。我曾经写过一篇比较通用的关于该模式的文章，即单例这种设计模式。

## 专题栏目 － Weex
#### 1. [快速上手](https://weex.incubator.apache.org/cn/guide/)
#### 2. [教程](https://weex.incubator.apache.org/cn/guide/)
#### 3. [手册](https://weex.incubator.apache.org/cn/references/)
#### 4. [参与](https://weex.incubator.apache.org/cn/guide/contributing.html)
#### 5. [工具](https://weex.incubator.apache.org/cn/playground.html)
#### 6. [常见问题](https://weex.incubator.apache.org/cn/faq.html)

## 开源库&项目&工具
#### 1. [Android 9-patch shadow generator](http://inloop.github.io/shadow4android/)
一个在线工具，通过 GUI 方式制作 .9 阴影背景图。

#### 2. [shadow-layout](https://github.com/dmytrodanylyk/shadow-layout)
Android Shadow Layout

#### 3. [Mscgen](http://www.mcternan.me.uk/mscgen/)
画时序图工具推荐

![Mscgen](http://www.mcternan.me.uk/mscgen/img/example0.png)

#### 4. [libco](https://github.com/Tencent/libco)
libco is a coroutine library which is widely used in wechat back-end service. It has been running on tens of thousands of machines since 2013.

## 联系方式
* Email：yanghui1986527#gmail.com
* Github: https://github.com/snowdream
* Blog: http://snowdream.github.io/blog/
* 简书：http://www.jianshu.com/u/748f0f7e6432
* 云栖博客：https://yq.aliyun.com/u/snowdream86 
* QQ群: 529327615     
* 微信公众号:  sn0wdr1am    

![sn0wdr1am](https://static.dingtalk.com/media/lADOmAwFCs0BAs0BAg_258_258.jpg)
