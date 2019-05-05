# 石杉的架构笔记 --互联网Java工程师进阶知识完全扫盲

[![original](https://badgen.net/badge/original/%E4%B8%AD%E5%8D%8E%E7%9F%B3%E6%9D%89/orange)]
[![open-source-organization](https://badgen.net/badge/organization/join%20us/138c7b)]
[![reading](https://badgen.net/badge/books/read%20together/cyan)]
[![coding](https://badgen.net/badge/leetcode/coding%20together/cyan)]
[![sharing](https://badgen.net/badge/readers/share%20together/cyan)]
[![stars](https://badgen.net/github/stars/doocs/wulimax/reactApp)]
[![forks](https://badgen.net/github/forks/wulimax/reactApp)]
[![contributors](https://badgen.net/github/contributors/wulimax/reactApp)]
[![help-wanted](https://badgen.net/github/label-issues/wulimax/reactApp/help%20wanted/open)]
[![issues](https://badgen.net/github/open-issues/wulimax/reactApp)]
[![PRs Welcome](https://badgen.net/badge/PRs/welcome/green)](http://makeapullrequest.com)

多年BAT一线大厂架构经验倾囊相授





## 编写目的

为了可以在面试前有一份资料能够帮助我们以最快的速度复习较为全面的知识点，一开始初衷想着只列出技术要点，能帮助回忆技术知识体系就行了。但是发现越整理知识越多，技术体系就越庞大。所以就想着分享出来，希望对大家有所帮助吧，哪怕一点点我也很高兴了，哈哈哈


## 分布式系统篇

###	分布式消息队
#### 消息如何顺序？
#### 消息重复如何解决？可以在中间层解决吗？MQ体系了解吗？

### 分布式搜索引擎
### [分布式缓存](https://github.com/wulimax/reactApp/blob/master/docs/DistributedCache/README.md) 

### [分库分表](https://github.com/wangjianfengnb/reactApp/tree/database-sharding/docs/DatabaseSharding)
### 分布式锁 
### [分布式事务](https://github.com/wulimax/reactApp/blob/master/docs/DistributedTransaction/README.md)
### [限流降级](https://github.com/wulimax/reactApp/blob/master/docs/RateLimit/README.md)



## Java功底篇
### 集合
### 并发
#### synchronized和lock的区别
#### ReentrantLock可重入锁是什么
#### java中的死锁如何排查和解决
#### CountDownLatch、CyclicBarrier、Semaphore分别是什么
#### java的内存模型是什么？能结合内存模型说一下volatile的工作原理吗？指令重排序，内存栅栏，happen-before等概念是指的什么意思？
#### java里玩儿悲观锁和乐观锁一般怎么玩儿？synchronized相当于是悲观锁，CAS相当于是乐观锁。知道CAS是什么吗？CAS是如何实现的？
#### 常用的线程池有哪些？不同线程池的使用场景是什么？说一下线程池配置的几个参数？线程池队列满的时候怎么处理（FixedThreadPool满了之后会怎么办）？线程池启动线程的原理（说说线程池的底层原理）？线程池被关闭的方式有哪几种？

### I/O
#### nio、bio、aio都是什么以及有什么区别？说说nio的原理？

### 网络
### netty

### [JVM]()
#### 如何解决线上系统JVM的OOM故障和GC性能调优？
#### 你们的线上系统的JVM都配置了哪些参数？
#### 你们的线上系统的JVM都配置了哪些参数？
#### jvm内存分为哪几个区域？哪些是线程独享？哪些是线程共享？对象从创建到销毁的生命周期里是如何在内存区域中转移的？
#### 哪些内存区域会参与gc回收？什么情况下一个对象会被gc掉？为什么要在这个时候让对象被gc？了解哪些jvm垃圾回收器？jvm有哪些gc算法？各种gc算法的优缺点是什么以及适用场景？新生代和老生代的gc回收策略是什么？cms垃圾回收器的原理是什么？何时触发minor gc？何时触发full gc？
#### 说说jvm的类加载机制？都有哪些类加载器以及分别加载哪些文件？类加载器之间的父子关系是什么？什么是双亲委派模型？如何自定义自己的类加载器？自己的类加载器和java自带的类加载器的关系如何处理？以下两种类加载方式有什么区别？class.forName()和classLoader？


### 公众号:石杉的架构笔记


## 数据库篇(MySQL)
### 索引
#### MySQ索引的原理和数据结构能介绍一下吗？b+树和b-树有什么区别？MySQL聚簇索引和非聚簇索引的区别是什么？他们分别是如何存储的？使用MySQL索引都有哪些原则？MySQL复合索引如何使用？
### 锁
#### 数据库锁有哪些类型？锁是如何实现的？MySQL行级锁有哪两种？一定会锁定指定的行么？为什么？悲观锁和乐观锁是什么？使用场景是什么？mysql死锁原理以及如何定位和解决？
### 日志
### 事物
#### 事务的几个特点是什么？数据库事务有哪些隔离级别？MySQL的默认隔离级别是？

如果大家想要实时关注我更新的文章以及分享的干货的话，可以关注我的公众号。

![我的公众号](https://github.com/wulimax/reactApp/blob/master/docs/PublicImage/shishan100.jpg)


### 关于转载
本仓库所有文章系石杉的架构笔记原创文章，如需转载，请联系公众号石杉的架构笔记获取授权，否则将追究法律责任。








