# Informal-Essay
前段时间自己总结了XMind，因为发现看的博客都是一知半解，需要自己整理一下，但是后来发现效果并不能很好的，还是边总结XMind，边总结博客，最后看看效果吧
## iOS
#### 需要学习的知识点

* 组件化
	* [Category 特性在 iOS 组件化中的应用与管控](https://tech.meituan.com/2018/11/08/ios-category-module-communicate.html)
		* 关键词 -- 依赖倒置原则
			* 依赖注入
			* 基于SPI机制
			* 基于通知中心
			* 使用objc_msgSend
* 自动化测试
	* [iOS 覆盖率检测原理与增量代码测试覆盖率工具实现](https://tech.meituan.com/2018/12/27/ios-increment-coverage.html)
		* 关键词
			* Macaca
	* [TBUIAutoTest](https://github.com/yulingtianxia/TBUIAutoTest)  
		* 顺便一提[MAcaca](https://github.com/macacajs/iosHookViewId)也是在采用这个框架
* MVVM
	* [ReactiveCocoa and MVVM, an Introduction 译文](http://www.cocoachina.com/ios/20150526/11930.html)
	* [ReactiveCocoa and MVVM, an Introduction](http://www.sprynthesis.com/2014/12/06/reactivecocoa-mvvm-introduction/)


* [RAC总结](https://github.com/MegahertzCHN/Blog/blob/master/RAC%E5%AD%A6%E4%B9%A0%E8%B7%AF%E7%BA%BF%E6%80%BB%E7%BB%93.md)
	* 蘑菇骨-李忠 
		* [李忠的博客](https://limboy.me/)
	* 美团
		* [美团关于RAC的博客](https://tech.meituan.com/tags/reactivecocoa.html)
		* [ReactiveCocoa核心元素与信号流](https://zhuanlan.zhihu.com/p/22959809)
	* 雷纯峰
		* [《ReactiveCocoa v2.5 源码解析之架构总览》](http://blog.leichunfeng.com/blog/2015/12/25/reactivecocoa-v2-dot-5-yuan-ma-jie-xi-zhi-jia-gou-zong-lan/)
		* [《Functor、Applicative 和 Monad》](http://blog.leichunfeng.com/blog/2015/11/08/functor-applicative-and-monad/ )
    * Raywenderlich
        * [ReactiveCocoa Tutorial – The Definitive Introduction: Part 1/2](https://www.raywenderlich.com/2493-reactivecocoa-tutorial-the-definitive-introduction-part-1-2)  
        * [ReactiveCocoa Tutorial – The Definitive Introduction: Part 2/2](https://www.raywenderlich.com/2490-reactivecocoa-tutorial-the-definitive-introduction-part-2-2)
        * [MVVM Tutorial with ReactiveCocoa: Part 1/2](https://www.raywenderlich.com/2346-mvvm-tutorial-with-reactivecocoa-part-1-2)
        * [MVVM Tutorial with ReactiveCocoa: Part 2/2](https://www.raywenderlich.com/2345-mvvm-tutorial-with-reactivecocoa-part-2-2)
    * 戴铭
        * [iOS函数响应式编程以及ReactiveCocoa的使用](https://ming1016.github.io/2016/08/09/how-to-use-reactivecocoa/)
        * [笔记](https://github.com/ming1016/study)
        * [iOS函数响应式编程以及ReactiveCocoa的使用](https://github.com/ming1016/study/wiki/iOS%E5%87%BD%E6%95%B0%E5%93%8D%E5%BA%94%E5%BC%8F%E7%BC%96%E7%A8%8B%E4%BB%A5%E5%8F%8AReactiveCocoa%E7%9A%84%E4%BD%BF%E7%94%A8)
        * [ReactiveCocoa Essentials: Understanding and Using RACCommand](http://codeblog.shape.dk/blog/2013/12/05/reactivecocoa-essentials-understanding-and-using-raccommand/)
        * [ReactiveCocoa Essentials: Understanding and Using RACCommand - 译文](http://zhoulingyu.com/2016/08/05/ReactiveCocoa%E6%A6%82%E8%A6%81%EF%BC%9A%E4%BA%86%E8%A7%A3%E5%92%8C%E4%BD%BF%E7%94%A8RACCommand/)
    * 绿梨子红苹果
        * [RAC中用RACCommand处理指令](http://blog.harrisonxi.com/2017/09/RAC%E4%B8%AD%E7%94%A8RACCommand%E5%A4%84%E7%90%86%E6%8C%87%E4%BB%A4.html)
        * [RAC中的冷信号与热信号](http://blog.harrisonxi.com/2017/09/RAC%E4%B8%AD%E7%9A%84%E5%86%B7%E4%BF%A1%E5%8F%B7%E4%B8%8E%E7%83%AD%E4%BF%A1%E5%8F%B7.html)
    * 南峰子
         * [MVVM Tutorial with ReactiveCocoa: Part 1/2 译文](https://southpeak.github.io/2014/08/08/mvvm-tutorial-with-reactivecocoa-1/)
        * [MVVM Tutorial with ReactiveCocoa: Part 2/2 译文](https://southpeak.github.io/2014/08/12/mvvm-tutorial-with-reactivecocoa-2/)
    * 王隆帅
        * [iOS Reactivecocoa（RAC）知其所以然（源码分析，一篇足以）](https://www.jianshu.com/p/15f9da230f82)
	* RAC图书
		* [Learn You a Haskell for Great Good!](http://learnyouahaskell.com/)

* Block
	* [iOS中__block 关键字的底层实现原理](https://www.jianshu.com/p/404ff9d3cd42)

* RunLoop
    * [Threading Programming Guide(2)](http://yulingtianxia.com/blog/2017/09/17/Threading-Programming-Guide-2/) 
    * [深入理解RunLoop](https://blog.ibireme.com/2015/05/18/runloop/)
    * [讨论 RunLoop 实现细节的视频 - 孙源](http://v.youku.com/v_show/id_XODgxODkzODI0.html)
    * [在 iOS APP 崩溃时弹出友好提示框](https://blog.moecoder.com/2016/07/30/show-a-friendly-alert-after-app-crashes/)
* RunTime
* 学习资料
    * [HIT-ALIBABA 笔试面试知识整理](https://hit-alibaba.github.io/interview/)
    * [戴铭 - 笔记](https://github.com/ming1016/study)
    * [阿里-p6-一面](https://mp.weixin.qq.com/s?__biz=MzUyNDM5ODI3OQ==&mid=2247483744&idx=1&sn=eb85b8e52612f5f413504856626c0df3&chksm=fa2cbac8cd5b33de463a12c1f188fc37f8d704898f6905fe210e43dbb0695281a8c855db8db2&scene=0&key=4f44f0a7d9d023745e10fd7e19ce672012c352f901a4282fa6bdac76408f87fb7d1184d9e0a3812196ca677c1aa45a6534761c482162516330111173fccb70a428cdbc6ae85d19f840b46a78f0436e46&ascene=0&uin=MTM1NjM2MjE2MA%3D%3D&devicetype=iMac)


## ReactNative
* 框架升级0.4x->0.59，升级框架问题参考
    * [React Native从0.39.x升级到0.49.x的那些事](https://www.cnblogs.com/yz1311/p/7889331.html)
    * [rn代码升级坑记](https://blog.99diary.com/2018/03/29/rn%E4%BB%A3%E7%A0%81%E5%8D%87%E7%BA%A7%E5%9D%91%E8%AE%B0/)
    * [React-Native 升级到 0.57.0 遇到的问题](https://kujiale-mobile.github.io/2018/10/29/rn-upgrade/)
        * [How To Upgrade Project to React-Native 0.57 (RN 0.57)](https://medium.com/@oleg2014/how-to-upgrade-project-to-react-native-0-57-rn-0-57-1a7e9fd8098)
        * [react-native-community/releases Changelog](https://github.com/react-native-community/releases/blob/master/CHANGELOG.md#057)
* 美柚
    * [美柚RN前端框架演进](http://lixingdecai.com/02/07/share_react_native/)

## 小程序
* [微信小程序开发资源汇总](https://github.com/justjavac/awesome-wechat-weapp)

## 宝藏
* 视频学习网站
    * [好奇猫学院](https://haoqicat.com/)
    
	
## Git管理
* [客户端单周发版下的多分支自动化管理与实践](https://tech.meituan.com/2019/01/10/traffic-git-branch-management.html)
* [改进合作 Git 工作流：自动提取、合并提交](https://tech.meituan.com/2014/03/28/improving-git-flow-squashing-commits.html)
* [Book - ProGit](https://git-scm.com/book/zh/v2)
	* [3.6 Git 分支 - 变基](https://git-scm.com/book/zh/v2/Git-%E5%88%86%E6%94%AF-%E5%8F%98%E5%9F%BA)
	* [3.2 Git 分支 - 分支的新建与合并](https://git-scm.com/book/zh/v2/Git-%E5%88%86%E6%94%AF-%E5%88%86%E6%94%AF%E7%9A%84%E6%96%B0%E5%BB%BA%E4%B8%8E%E5%90%88%E5%B9%B6#r_basic_merging)
* [git基本工作流及rebase介绍](http://blog.harrisonxi.com/2017/03/git%E5%9F%BA%E6%9C%AC%E5%B7%A5%E4%BD%9C%E6%B5%81%E7%A8%8B%E5%8F%8Arebase%E4%BB%8B%E7%BB%8D.html)

## 代码规范
* iOS
	* [objc-zen-book](https://github.com/objc-zen/objc-zen-book#preface)
	* 
* ReactNative
	* [React Native工程中TSLint静态检查工具的探索之路](https://tech.meituan.com/2019/01/17/exploring-the-tslint-static-checking-tool-on-the-react-native-project.html)

## 公共的API
* [豆瓣列表](https://api.douban.com/v2/movie/in_theaters?apikey=0b2bdeda43b5688921839c8ecb20399b&city=%E5%8C%97%E4%BA%AC&start=0&count=100&client=&udid=)

## 欣赏的Blog
#### 后起之秀（还在更新）

|作者|链接|就职|曾任职|喜欢|备注|
|---|---|---|---|---|---|
|李忠|https://limboy.me/category/tech.html|---|蘑菇街|组件化|---|
|杨萧玉|http://yulingtianxia.com/|腾讯|---|自动测试|---|
|chenyilong|https://www.jianshu.com/u/96a14318a4de|阿里|---|---|---|
|唐巧|https://blog.devtang.com/|猿题库|---|---|---|
|绿梨子红苹果|http://blog.harrisonxi.com/|阿里-天猫|bilibili|RAC|---|
|王隆帅|https://www.jianshu.com/u/1a9cd48c3cf0|美团|---|RAC|---|
|---|---|---|---|---|---|

#### 已经不更新
|作者|链接|就职|曾任职|喜欢|备注|
|---|---|---|---|---|---|
|雷纯峰|http://blog.leichunfeng.com/|阿里|---|MVVM&&ReactiveCocoa|---|
|郭曜源|https://blog.ibireme.com/|---|百度|RunLoop|---|
|孙源|http://blog.sunnyxx.com/|百度|---|RunTime&RunLoop&面试&代码规范|---|
|南峰子|https://southpeak.github.io/|京东金融|---|RAC|---|
|---|---|---|---|---|---|
