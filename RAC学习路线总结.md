**RAC学习路线总结：**

最近一直在看RAC的文章，以下是我看的博客，给大家一些参考，难度依次升高。

参考链接是以前一篇巧神的博客：[ReactiveCocoa 讨论会](https://blog.devtang.com/2016/01/03/reactive-cocoa-discussion/),因为我主要是看了美团的技术博客，所以大部分总结的都是关于美团技术博客的文章，如果大家对我的学习路线不敢兴趣，可以坐[直通车](https://tech.meituan.com/tags/reactivecocoa.html)，直接学习。

以下是我觉得受益匪浅的博客地址：

* 1. 使我是入门的是两篇简单的英文文档，即使是两篇英文博客，但是非常的容易理解，即使是英语不好的我，也可以看个大概。实际上分为上下两篇，大家可以在Demo里面理解自己代码的意思，一步一步下来很有成就感。
    * 1.1 [RACSignal的基本用法1](https://www.raywenderlich.com/2493-reactivecocoa-tutorial-the-definitive-introduction-part-1-2)  
    * 1.2 [RACSignal的基本用法2](https://www.raywenderlich.com/2490-reactivecocoa-tutorial-the-definitive-introduction-part-2-2)
* 2. 接下来看的是美团的分析，美团推荐和雷纯峰看我推荐的前两篇文章。接下来这篇文章更进一步的分析了RACSignal原理，代码跟1.1紧密相连的，所以1.1是需要大家仔细看一下的。
    * [RACSignal的Subscription的深入研究](https://tech.meituan.com/RAC_Signal_Subscription.html)
* 3. 了解了正常的RACSignal，我们就可以了解一下关于冷热信号的概念了。以下是美团总结的三个冷热信号的概念和详细解释了为什么需要了解冷热信号的区别，对于工程有哪些影响。
    * 3.1 [细说ReactiveCocoa的冷信号与热信号（一）](https://tech.meituan.com/talk_about_reactivecocoas_cold_signal_and_hot_signal_part_1.html)，
    * 3.2 [细说ReactiveCocoa的冷信号与热信号（二）](https://tech.meituan.com/talk_about_reactivecocoas_cold_signal_and_hot_signal_part_2.html)，
    * 3.3 [细说ReactiveCocoa的冷信号与热信号（三）](https://tech.meituan.com/talk_about_reactivecocoas_cold-signal_and_hot_signal_part_3.html) ~~看了一下，我好像3.3没有看，😓淡定淡定，秀儿坐下！！！~~已经看过了，偶觉得他们好厉害呀！15年就写出了我现在要学的文章，666~
* 4. 巧神在博客中当时讨论了一下关于雷纯峰的技术博客，我看了几篇，其中：[ReactiveCocoa v2.5 源码解析之架构总览](http://blog.leichunfeng.com/blog/2015/12/25/reactivecocoa-v2-dot-5-yuan-ma-jie-xi-zhi-jia-gou-zong-lan/)，其实大家看了这些博客主要是学习MVVM架构，所以实践篇[MVVM With ReactiveCocoa](http://blog.leichunfeng.com/blog/2016/02/27/mvvm-with-reactivecocoa/)
* 5. 巧神的[ReactiveCocoa - iOS开发的新框架](http://blog.devtang.com/2014/02/11/reactivecocoa-introduction/)，我还没看，备注

**总结：**

* 关于冷热信号的结论：
    * 1.RACSubject及其子类都是热信号。
    * 2.RACSignal除了RACSubject类及其子类外都是冷信号。
* 大家所说的MVC是不便于测试的，不是纯函数的，代码抽离不方便的，MVVM几乎涵盖了所有的优势。
    * 其实大家接触多了以后就会发现很多Rx开头的都是以这种架构来进行解耦，所以很大程度都是一样的。
    * 在了解了一些RN的相关只是以后，你会觉得实际上Redux和Rx所干的事情都是一样的，大家都是基于纯函数的逻辑，保持这一个线程的干净程度，所以鄙人认为都是差不多的。
    * 大家保重身体，路漫漫兮修远兮...




