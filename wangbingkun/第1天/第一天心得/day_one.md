上午：上午主要学习了线程的创建与调度，在上午的实际操作过程中，创建的线程由于没有延时导致一直在占用cpu资源所以动态线程并未创建成功而导致信息没有输出,加入延时后顺利解决

下午：主要学习了rtt的启动流程以及软件定时器，但是在软件定时器的使用过程中我先将定时器配置为RT_TIMER_FLAG_SOFT_TIMER|FLAG_ONE_SHOT，定时器单次计时后并未关闭，而改成FLAG_ONE_SHOT|RT_TIMER_FLAG_SOFT_TIMER定时器就是单次，按理说是一样但是实际运行不是，不知道是我的问题还是什么。下午启动流程的学习中并未听太懂，课下自己找了一遍才感觉疏通许多。

