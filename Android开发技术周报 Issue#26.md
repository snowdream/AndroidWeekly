# Android开发技术周报 Issue#26

    声明：所有内容收集整理自网络。如有侵权，请联系删除。微信公众号上请点击“阅读原文”阅读完整版本。
    
## 业界新闻
#### 1. [ECMAScript 2017 语言规范发布](https://www.oschina.net/news/86699/ecmascript-2017standards)
Ecma 国际公布了第八版的 ECMAScript 语言规范 ECMAScript 2017(或 ES8)。

#### 2. [谷歌暗示：Android 8.0系统正式版即将到来](https://www.ithome.com/html/android/315355.htm)
从谷歌发布信息来看，谷歌会于本月底推送Android 8.0的最后一个开发者预览版，此版本将接近于最终正式版。据外媒softpedia报道，谷歌已经证实Android 8.0的正式版会在2017年第三季度正式发布，最快下月底推出。首批机型包括Google Pixel和Google Pixel XL，以及Nexus 5X和Nexus 6p。

## Android开发
#### 1. [微信Android模块化架构重构实践](http://t.cn/RKSHl7i)
微信Android诞生之初，用的是常见的分层结构设计。这种架构简单、清晰并一直沿袭至今。这是微信架构的v1.x时代。

#### 2. [从Ant到Gradle的迁移之路](http://t.cn/RKSHsWH)
由于Gradle的种种优点（大家可以参考网上的资料，这里不多说了），前一段时间项目组打算将原来的Ant编译打包方式迁移到Gradle编译打包方式。
现在迁移基本完成，我这里将迁移过程遇到的坑以及经验做一个总结，希望能给大家在Ant转Gradle的时候带来一些提示。

#### 3. [C++17 相比于 C++14 的所有重大变化](http://t.cn/RKSQsZA)
本文档列举了自C++14发布以来，到C++17 DIS（N4660）发布为止，应用于C++工作草案（working draft）的所有重大变化。重大变化（major changes）是以专门的文件（paper）的形式加入的。不是每个文件都单独在此提及，没有单独提及的文件在下面简要列出。CWG或LWG问题清单（issue list）中的问题解决方案（issue resolution）通常不包括在重大变化之内，但是包含问题解决方案的文件也会简要列出。

#### 4. [热修复之 Method Hook 原理分析](https://pqpo.me/2017/07/07/hotfix-method-hook/)
本篇文章主要分析以 AndFix 为代表的底层方法替换方案，并且实现了《深入探索 Android 热修复技术原理》中提到得更为优雅，兼容性更好的方法替换新方案（MethodHook）。

#### 5. [在 Kotlin 语言中调用 JavaScript 方法](https://coyee.com/article/12318-calling-javascript-from-kotlin)
Kotlin 已被设计为能够与 Java 平台轻松互操作。它将 Java 类视为 Kotlin 类，并且 Java 也将 Kotlin 类视为 Java 类。但是，JavaScript 是一种动态类型语言，这意味着它不会在编译期检查类型。你可以通过动态类型在 Kotlin 中自由地与 JavaScript 交流，但是如果你想要 Kotlin 类型系统的全部威力 ，你可以为 JavaScript 库创建 Kotlin 头文件。

## 专题栏目 － Glide
#### 1. [开始！](https://mrfu.me/2016/02/27/Glide_Getting_Started/)
#### 2. [加载进阶](http://mrfu.me/2016/02/27/Glide_Advanced_Loading/)
#### 3. [ListAdapter(ListView, GridView)](http://mrfu.me/2016/02/27/Glide_ListAdapter_(ListView,_GridView)/)
#### 4. [占位符 和 渐现动画](http://mrfu.me/2016/02/27/Glide_Placeholders_&_Fade_Animations/)
#### 5. [图片重设大小 和 缩放](http://mrfu.me/2016/02/27/Glide_Image_Resizing_&_Scaling/)
#### 6. [显示 Gif 和 Video](http://mrfu.me/2016/02/27/Glide_Displaying_Gifs_&_Videos/)
#### 7. [缓存基础](http://mrfu.me/2016/02/27/Glide_Caching_Basics/)
#### 8. [请求优先级](http://mrfu.me/2016/02/27/Glide_Request_Priorities/)
#### 9. [缩略图](http://mrfu.me/2016/02/27/Glide_Thumbnails/)
#### 10. [回调：SimpleTarget 和 ViewTarget 用于自定义视图类](http://mrfu.me/2016/02/27/Glide_Callbacks_SimpleTarget_and_ViewTarget_for_Custom_View_Classes/)
#### 11. [加载图片到通知栏和应用小部件中](http://mrfu.me/2016/02/27/Glide_Loading_Images_into_Notifications_and_AppWidgets/)
#### 12. [异常：调试和错误处理](http://mrfu.me/2016/02/28/Glide_Exceptions-_Debugging_and_Error_Handling/)
#### 13. [自定义转换](http://mrfu.me/2016/02/28/Glide_Custom_Transformations/)
#### 14. [用 animate() 自定义动画](http://mrfu.me/2016/02/28/Glide_Custom_Animations_with_animate()/)
#### 15. [集成网络栈](http://mrfu.me/2016/02/28/Glide_Integrating_Networking_Stacks/)
#### 16. [用 Module 自定义 Glide](http://mrfu.me/2016/02/28/Glide_Customize_Glide_with_Modules/)
#### 17. [Module 实例：接受自签名证书的 HTTPS](http://mrfu.me/2016/02/28/Glide_Module_Example_Accepting_Self-Signed_HTTPS_Certificates/)
#### 18. [Module 实例：自定义缓存](http://mrfu.me/2016/02/28/Glide_Module_Example_Customize_Caching/)
#### 19. [Module 实例：用自定义尺寸优化加载的图片](http://mrfu.me/2016/02/28/Glide_Module_Example_Optimizing/)
#### 20. [动态使用 Model Loader](http://mrfu.me/2016/02/28/Glide_Dynamically_Use_Model_Loaders/)
#### 21. [如何旋转图像](http://mrfu.me/2016/02/28/Glide_How_to_Rotate_Images/)
#### 22. [系列综述](http://mrfu.me/2016/02/28/Glide_Series_Roundup/)


## 开源库&项目&工具
#### 1. [mimecraft](https://github.com/square/mimecraft)
Utility for creating RFC-compliant multipart and form-encoded HTTP request bodies. http://square.github.io/mimecraft/

#### 2. [turn-layout-manager](https://github.com/cdflynn/turn-layout-manager)
A carousel layout manager for RecyclerView

#### 3. [ViewAnimator](https://github.com/florent37/ViewAnimator)
A fluent Android animation library

#### 4. [RichPath](https://github.com/tarek360/RichPath)
💪 Rich Android Path. :clown_face: Draw as you want. 🎉 Animate much as you can.
![RichPath](https://github.com/tarek360/RichPath/raw/master/screenshots/header.gif)

#### 5. [uCrop](https://github.com/Yalantis/uCrop)
Image Cropping Library for Android

## 联系方式
* Email：yanghui1986527#gmail.com
* Github: https://github.com/snowdream
* Blog: http://snowdream.github.io/blog/
* 简书：http://www.jianshu.com/u/748f0f7e6432
* 云栖博客：https://yq.aliyun.com/u/snowdream86 
* QQ群: 529327615     
* 微信公众号:  sn0wdr1am    

![sn0wdr1am](https://static.dingtalk.com/media/lADOmAwFCs0BAs0BAg_258_258.jpg)
