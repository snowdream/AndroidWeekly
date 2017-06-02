# Android开发技术周报 Issue#20

    声明：所有内容收集整理自网络。如有侵权，请联系删除。微信公众号上请点击“阅读原文”阅读完整版本。
    
## 业界新闻
#### 1. [Java 9 又要推迟了，Java 首席架构师是这样解释的](http://t.cn/RSJ0UYS)
甲骨文 Java 平台组首席架构师 Mark Reinhold 提议「调整发布日期，以多给 JCP 一些时间」。Java 9 的发布时间往后推迟 8 周，也就是到 9 月 21 日发布。

## Android开发
#### 1. [我一行代码都不写实现Toolbar!你却还在封装BaseActivity?](http://www.jianshu.com/p/75a5c24174b2)
说说怎么在不使用继承的情况下让 Activty 一行代码都不写就能实现 Toolbar。

#### 2. [PermissionsDispatcher，Android 6.0 运行时权限](http://www.jianshu.com/p/64e7334cde11)
运行时权限的加入增加了用户隐私的安全，但同时也给开发者带来了一些负担，因为多了检查权限，请求权限，处理权限请求响应的步骤。
于是就出现了一些框架，用于简化运行时权限的处理，如 PermissionsDispatcher，Dexter，RxPermissions，easypermissions 等。

#### 3. [Android 光传感器开发详细教程](http://www.jianshu.com/p/bb3952ff2324)
光线感应器( Light Sensor )：光传感器主要用来检测手机周围光的强度，与其他传感器不同的是，该传感器监测手机周围光的强度，且单位为 lux。光传感器的开发与其他各种传感器的开发步骤基本相同，只是监测的是 Sensor.TYPE_LIGHT。如果学会了光感器的开发，开发其他的传感器则只需要改变监听器对象及注册监听的方法，然后根据每个人不同的业务需求，来修改后续的逻辑。

#### 4. [Android 动画：手把手教你使用 补间动画](http://www.jianshu.com/p/733532041f46)
本文将详细介绍 Android 动画中 补间动画的原理 & 使用

#### 5. [小程序组件化框架 WePY 在性能调优上做出的探究](http://t.cn/RSJ09ij)
本文旨在介绍两点在小程序开发过程当中碰到的一些性能问题以及 WePY 的一些优化方案。

#### 6. [触动时刻：移动应用成功秘诀（一）](http://t.cn/RSJpdaB)
“触动时刻” 是一个个决定如今消费行为至关重要的 “触点”，只有尽可能多地在这些触点上打动消费者，才能最终决定他们的去向。

## 专题栏目 － Annotation-Processing-Tool
#### 1. [ANNOTATION PROCESSING 101](http://hannesdorfmann.com/annotation-processing/annotationprocessing101)
In this blog entry I would like to explain how to write an annotation processor. So here is my tutorial. First, I am going to explain to you what annotation processing is, what you can do with that powerful tool and finally what you cannot do with it. In a second step we will implement a simple annotation processor step by step.

#### 2. [Annotation-Processing-Tool详解](http://www.open-open.com/lib/view/open1470735314518.html)
在这篇文章中我将阐述如何实现一个注解处理器。首先我将向你解释什么是注解处理器，你可以使用这个强大的工具来做什么及不能做什么。接下来我们将一步一步来实现一个简单的注解处理器。

#### 3. [Android注解使用之注解编译android-apt如何切换到annotationProcessor](http://www.cnblogs.com/whoislcj/p/6148410.html)
自从EventBus 3.x发布之后其通过注解预编译的方式解决了之前通过反射机制所引起的性能效率问题，其中注解预编译所采用的的就是android-apt的方式，不过最近Apt工具的作者宣布了不再维护该工具了，因为Android Studio推出了官方插件，并且可以通过gradle来简单的配置，它就是annotationProcessor，今天来学习一下如何将原来的android-apt切换到annotationProcessor。

#### 4. [Java注解处理器](https://race604.com/annotation-processing/)
Java中的注解(Annotation)是一个很神奇的东西，特别现在有很多Android库都是使用注解的方式来实现的。一直想详细了解一下其中的原理。很有幸阅读到一篇详细解释编写注解处理器的文章。本文的原文是ANNOTATION PROCESSING 101，作者是Hannes Dorfmann。这是一篇好文，忍不住翻译学习一下。以下是翻译。（注：本文的翻译已经获得了作者 Hannes 的授权。）

#### 5. [Android公共技术点之二-Annotation Processing Tool](http://yeungeek.com/2016/04/27/Android公共技术点之二-Annotation-Processing-Tool/)
在技术点之一中介绍到编译时注解，使用APT工具进行自动解析，这次介绍的就是Annotation Processing Tool

#### 6. [JavaPoet的基本使用](http://blog.csdn.net/crazy1235/article/details/51876192)
JavaPoet 是一个用来生成 .Java源文件的Java API。
当做如注解或者数据库模式、协议格式等事情时，生成源文件就比较有用处。

## 开源库&项目&工具
#### 1. [kotlin-statistics](https://github.com/thomasnield/kotlin-statistics)
Idiomatic statistical operators for Kotlin

#### 2. [from-java-to-kotlin](https://github.com/MindorksOpenSource/from-java-to-kotlin)
From Java To Kotlin - Your Cheat Sheet For Java To Kotlin

#### 3. [kotterknife](https://github.com/JakeWharton/kotterknife)
View "injection" library for Android

#### 4. [kotlin-options](https://github.com/peter-tackage/kotlin-options)
Kotlin Options with functional operators made using sealed classes

#### 5. [android-mvp-kotlin-starter](https://github.com/ravidsrk/android-mvp-kotlin-starter)
An MVP Boilerplate to save me having to create the same project over from scratch every time!

#### 6. [gradle-script-kotlin](https://github.com/gradle/gradle-script-kotlin)
Kotlin language support for Gradle build scripts

## 联系方式
* Email：yanghui1986527#gmail.com
* Github: https://github.com/snowdream
* Blog: http://snowdream.github.io/blog/
* 简书：http://www.jianshu.com/u/748f0f7e6432
* 云栖博客：https://yq.aliyun.com/u/snowdream86 
* QQ群: 529327615     
* 微信公众号:  sn0wdr1am    

![sn0wdr1am](https://static.dingtalk.com/media/lADOmAwFCs0BAs0BAg_258_258.jpg)
