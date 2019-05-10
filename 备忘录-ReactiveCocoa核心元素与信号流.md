### RAC信号流
* bind/flattenMap:返回一个全新的信号
	* flattenMap优点：添加安全检查，推荐flattenMap
* map操作可将原信号输出的数据通过自定义的方法转换成所需的数据， 同时将变化后的数据作为新信号的输出。
* flatten: 该操作主要作用于信号的信号。
* switchToLatest：与flatten相同，其主要目的也是用于"压平"信号的信号。
* scanWithStart : 该操作可将上次reduceBlock处理后输出的结果作为参数，传入当次reduceBlock操作，往往用于信号输出值的聚合处理。
* throttle:这个操作接收一个时间间隔interval作为参数，如果Signal发出的next事件之后interval时间内不再发出next事件，那么它返回的Signal会将这个next事件发出。




#### 参考链接
* [ReactiveCocoa核心元素与信号流](https://zhuanlan.zhihu.com/p/22959809)