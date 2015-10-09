# Android技能树

__*说明：该文档用来总结Android开发相关技能点，以供Android开发人员自我检测，相互学习，也可以作为Android新手的学习参考，欢迎大家查漏补缺、多提意见及修正一些不恰当的地方，希望在大家的共同努力下不断完善*__




## 非Android相关基础
* 数据解析（XML/json）
* http
* Linux基础（非必须，但掌握的话对深刻理解Android有好处）
* java core




## 入门
- **官方入门教程：**http://developer.android.com/develop/index.html

#### 开发环境搭建
** 两大主流集成开发环境：**
* Android Studio（这是Google为Android提供的开发工具，**推荐**使用）
* Eclipse（早期流行Android开发工具，逐渐被Android Studio 替代）
下载地址及配置请查看官方文档或者Google百度
*官方环境搭建：*http://developer.android.com/sdk/index.html

#### 第一个Android程序、熟悉工程结构
- **官方教程：**http://developer.android.com/training/index.html

#### Android简介
- http://developer.android.com/guide/index.html

#### [各种开发工具介绍：](http://developer.android.com/sdk/index.html)
- 开发环境、模拟器真机运行app、测试工具、性能测试




## Android核心基础
- 官网介绍：http://developer.android.com/guide/index.html

#### [基本组件：](http://developer.android.com/guide/components/index.html)
- [Intents and Intent Filters](http://developer.android.com/guide/components/intents-filters.html)
- [Activities](http://developer.android.com/guide/components/activities.html)
- [Services](http://developer.android.com/guide/components/services.html)
- [Content Providers](http://developer.android.com/guide/topics/providers/content-providers.html)（了解即可）
- [Processes and Threads](http://developer.android.com/guide/components/processes-and-threads.html)

#### [资源](http://developer.android.com/guide/topics/resources/index.html)
- [Providing Resources](http://developer.android.com/guide/topics/resources/providing-resources.html)
- [Accessing Resources](http://developer.android.com/guide/topics/resources/accessing-resources.html)
- [Resources Types](http://developer.android.com/guide/topics/resources/available-resources.html)

#### [Manifest.xml文件介绍](http://developer.android.com/guide/topics/manifest/manifest-intro.html)

#### [用户界面：](http://developer.android.com/guide/topics/ui/index.html)
各种UI基础效果的实现和基础控件的使用可参考官方demo程序

* 常用布局
* 常用控件
* 输入控制
* 输入事件
* 菜单
* Action Bar
* 对话框
* 通知
* Toasts（简单提示消息）
* 手势拖拉（了解即可）
* 样式和主题
* 自定义UI控件入门

#### [动画和图形](http://developer.android.com/guide/topics/graphics/index.html)
- 重点掌握动画的种类和实现（参照官方动画demo学习），其他了解

#### [数据存储](http://developer.android.com/guide/topics/data/index.html)
- Shared Preferences
- Internal Storage
- External Storage
- SQLite Databases
- Network Connection

#### 屏幕适配




## Android进阶
#### 必备开源框架的学习
* 网络请求开源框架
* 数据库开源框架
* 图片加载及处理开源框架
* 数据解析开源框架
* ...

#### 各种专题学习
* [官网一些专题：](http://developer.android.com/training/index.html)**
* 性能测试和优化(listview优化、布局优化等)
* 多线程（后台任务处理，非UI线程与UI线程之间的通信）（必须掌握）
* 自定义View
* 多谋体开发（相机、音视频播放）
* 图形和动画深入学习
* 地图接入
* 传感器
* 应用方法数超过65K的解决办法
* ...

#### 商业项目必备
* 数据统计（自己开发or第三方如友盟）
* 线上bug统计
* 消息推送
* 开放平台接入（按需学习）
* 应用发布（签名、打包、测试包、正式包、渠道包等概念的理解及具体操作）

#### 常见开发问题
* OOM
* ANR
* listview卡顿
* 如何正确退出程序及activity管理
* ...




## Android高级
* native开发、rom、系统原理、驱动开发...？




## 学习方法建议
在对Android从宏观上有个初步的认识、掌握开发环境的搭建、对Android应用结构有基本了解之后，可以根据开发需要，找到对应的官方例子代码或者网上搜索例子代码进行学习开发。

- **官网地址：**http://developer.android.com/index.html
- **官方例子：**提供了各种api的使用demo，有非常大的学习价值，demo获取方法，一种办法是通过sdk管理器下载到本地，若已经下载完位置位于sdk/samples目录下，还有一种获取demo的方法是在Android Studio里面导入，[具体方法](http://developer.android.com/samples/index.html)




## 学习资源
在前面技能点里面有针对介绍，主要是Android官网文档+官方demo+Google+百度+github+网络视频，英文不太好的可以考虑买本书。哪本书好？基础Android的书籍貌似没看过，自行Google、百度，或者哪位有经验的大侠推荐一下吧。




## 自测题
1. Android四大组件？
2. Activity的生命周期及各个生命周期回调方法适合做什么事情？
3. 如何防止ANR？
5. 什么是Service？应用场景？如何代码实现？IntentService有什么特点？
6. 什么是.9图片？应用场景？如何使用制作和使用？
7. Activity的启动模式？
8. 如何在非UI线程刷新UI界面？
9. Handler机制？
10. ListView优化？
11. 数据存储方式有几种？每一种的应用场景？
12. xml解析方式有多少种？各种之间的差异？json解析框架？xml和json之间的区别和优劣？
13. ...








