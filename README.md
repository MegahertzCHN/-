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
	* RAC图书
		* [Learn You a Haskell for Great Good!](http://learnyouahaskell.com/)

* Block
	* [iOS中__block 关键字的底层实现原理](https://www.jianshu.com/p/404ff9d3cd42)

* RunLoop
	* [Threading Programming Guide(2)](http://yulingtianxia.com/blog/2017/09/17/Threading-Programming-Guide-2/) 
	* [深入理解RunLoop](https://blog.ibireme.com/2015/05/18/runloop/)
* RunTime


## ReactNative

	
## Git管理
* [客户端单周发版下的多分支自动化管理与实践](https://tech.meituan.com/2019/01/10/traffic-git-branch-management.html)
* [改进合作 Git 工作流：自动提取、合并提交](https://tech.meituan.com/2014/03/28/improving-git-flow-squashing-commits.html)
* [Book - ProGit](https://git-scm.com/book/zh/v2)
	* [3.6 Git 分支 - 变基](https://git-scm.com/book/zh/v2/Git-%E5%88%86%E6%94%AF-%E5%8F%98%E5%9F%BA)
	* [3.2 Git 分支 - 分支的新建与合并](https://git-scm.com/book/zh/v2/Git-%E5%88%86%E6%94%AF-%E5%88%86%E6%94%AF%E7%9A%84%E6%96%B0%E5%BB%BA%E4%B8%8E%E5%90%88%E5%B9%B6#r_basic_merging)

## 代码规范
* iOS
	* [objc-zen-book](https://github.com/objc-zen/objc-zen-book#preface)
	* 
* ReactNative
	* [React Native工程中TSLint静态检查工具的探索之路](https://tech.meituan.com/2019/01/17/exploring-the-tslint-static-checking-tool-on-the-react-native-project.html)

## 欣赏的Blog
#### 后起之秀（还在更新）

|作者|链接|就职|曾任职|喜欢|备注|
|---|---|---|---|---|---|
|李忠|https://limboy.me/category/tech.html|---|蘑菇街|组件化|---|
|杨萧玉|http://yulingtianxia.com/|腾讯|---|自动测试|---|
|chenyilong|https://www.jianshu.com/u/96a14318a4de|阿里|---|---|---|
|唐巧|https://blog.devtang.com/|猿题库|---|---|---|
|---|---|---|---|---|---|

#### 已经不更新
|作者|链接|就职|曾任职|喜欢|备注|
|---|---|---|---|---|---|
|雷纯峰|http://blog.leichunfeng.com/|阿里|---|MVVM&&ReactiveCocoa|---|
|郭曜源|https://blog.ibireme.com/|---|百度|RunLoop|---|
|孙源|http://blog.sunnyxx.com/|百度|---|RunTime&RunLoop&面试&代码规范|---|
|---|---|---|---|---|---|
