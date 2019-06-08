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





## 目录

- [Java](#java)
    - [基础](#基础)
    - [集合](#集合)
    - [并发](#并发)
    - [JVM](#jvm)
    - [I/O](#io)
    - [Dubbo](#Dubbo)
    - [netty](#netty)
- [网络](#网络)
- [操作系统](#操作系统)
    - [Linux相关](#linux相关)
- [数据结构与算法](#数据结构与算法)
    - [数据结构](#数据结构)
    - [算法](#算法)
- [数据库](#数据库)
    - [MySQL](#mysql)
    - [Redis](#redis)
    - [mongodb](#mongodb)
- [高可用高性能的分布式系统设计](#高可用高性能的分布式系统设计)
    - [分布式消息队列](#分布式消息队列)
    - [分布式搜索引擎](#分布式搜索引擎)
- [面试指南](#面试指南)
    - [备战面试](#备战面试)
    - [常见面试题总结](#常见面试题总结)
    - [面经](#面经)
- [工具](#工具)
    - [Git](#git)
    - [Docker](#Docker)

### 	[并发](https://github.com/wulimax/reactApp/blob/master/docs/DataConcurrent/README.md)



### 	[JVM](https://github.com/wulimax/reactApp/blob/master/docs/ZhJVM/README.md)


### 算法

- [每日一练](https://leetcode-cn.com/)


## 面试指南

### 备战面试
- [面试一线互联网大厂？那这道题目你必须得会！](https://mp.weixin.qq.com/s?__biz=MzU0OTk3ODQ3Ng==&mid=2247484645&idx=1&sn=663238af983603a4c0b33cf42c3ebbcf&chksm=fba6ece6ccd165f0d78f271a21fdc1b91ad8d3def896e2f4df79d9c8d4cf99e3b2978d703dde&mpshare=1&scene=1&srcid=0608edSfhNw7AIjzl9R54Sih%23rd)
- [阿里三面，P9面试官是如何360°无死角考察候选人的？](https://mp.weixin.qq.com/s?__biz=MzU0OTk3ODQ3Ng==&mid=2247485021&idx=1&sn=936b0ecbbe8bd633b1a6c10127eaf4c4&chksm=fba6ee5eccd167483e2a5b17df3f3d1f38f9b98b894f3c47d6b365821338e1380f7c6af1a49d&mpshare=1&scene=1&srcid=0608bZo70WnyWgBMGZs9aAPA%23rd)
- [互联网公司的面试官是如何360°无死角考察候选人的？（上篇）](https://mp.weixin.qq.com/s?__biz=MzU0OTk3ODQ3Ng==&mid=2247484144&idx=1&sn=a6b86d38a762e317ba78e2500fb1a8ff&chksm=fba6eaf3ccd163e5403a01be51216780040511b2ddc4d5750ace6e46b4242ceaf77d0432c680&mpshare=1&scene=1&srcid=0608Ls6BQxXTdAQKvDeZx8f0%23rd)
- [互联网公司面试官是如何360°无死角考察候选人的？（下篇）](https://mp.weixin.qq.com/s?__biz=MzU0OTk3ODQ3Ng==&mid=2247484148&idx=1&sn=a2e05fed6b2dda661b4da11036b883a9&chksm=fba6eaf7ccd163e19013c4204fd0997159b04cd37a235d05dab4f645b61b2f8f9e21a98614c8&mpshare=1&scene=1&srcid=0608k7qLNodHSqW0SbfpZLRG%23rd)
- [中小公司的Java工程师应该如何逆袭冲进BAT？](https://mp.weixin.qq.com/s?__biz=MzU0OTk3ODQ3Ng==&mid=2247484442&idx=1&sn=610f02aa18ef6a5d8c80a74959be0333&chksm=fba6ec19ccd1650fc265ac6f7f462157a7b274e358282bb7fc029e9366cfac656c58300b98c5&mpshare=1&scene=1&srcid=06089lyagf3w18D90N7RcB8q%23rd)
- [【offer收割机必备】我简历上的Java项目都好low，怎么办？](https://mp.weixin.qq.com/s?__biz=MzU0OTk3ODQ3Ng==&mid=2247484583&idx=1&sn=a9d43c3ee63c8e5a37c073c2b8c43fba&chksm=fba6eca4ccd165b2602a462c5589fa8dacd78558bdee7e0138b02bb26370637714f1094f4e9f&mpshare=1&scene=1&srcid=0608607GubfCXM2YaAqOLXET%23rd)
- [Java工程师如何在1个月内做好面试准备？](https://mp.weixin.qq.com/s?__biz=MzU0OTk3ODQ3Ng==&mid=2247484575&idx=1&sn=7075fb3a42ef62fb5e69c868f29c8c61&chksm=fba6ec9cccd1658a391bc4e60faa35b44b947dbb6f535042e392c668693524447a2604955fd8&mpshare=1&scene=1&srcid=0608BvwQetAYtHkxZX7X7r8F%23rd)
### 常见面试题总结
- [互联网大厂Java面试题：使用无界队列的线程池会导致内存飙升吗？](https://mp.weixin.qq.com/s?__biz=MzU0OTk3ODQ3Ng==&mid=2247484480&idx=1&sn=1c7262d7f185ad6f99b840fb7779a575&chksm=fba6ec43ccd16555d826772a530c280548d8fd9785a9169b87bb4ed82d8b12ad75154c98b957&mpshare=1&scene=1&srcid=0608DxO0IKPDPxNOoN1la590%23rd)
- [阿里一面：关于【缓存穿透、缓存击穿、缓存雪崩、热点数据失效】问题的解决方案](https://mp.weixin.qq.com/s?__biz=MzU0OTk3ODQ3Ng==&mid=2247484884&idx=1&sn=ceb798b6e8ef0ee608a992385f7d8568&chksm=fba6edd7ccd164c155271811f7948b476955cab41b23f2333847b8c268b31cc9f3332c2e3926&mpshare=1&scene=1&srcid=0608pIX1L8Fja1H99IyorW2X%23rd)


### 面经
- [小公司面试10连挂之后，我拿到了互联网一线大厂offer！](https://mp.weixin.qq.com/s?__biz=MzU0OTk3ODQ3Ng==&mid=2247484955&idx=1&sn=be39f51e00d78eb7d3a4ae6b7137e62c&chksm=fba6ee18ccd1670ec7dbf62f2c73d65b241cfb6897bac9316981c1e7936e31c1caee5ccee87e&mpshare=1&scene=1&srcid=0608zdpqBAGKWQr6ExuWOvtg%23rd)
- [尴尬的面试现场：说说你们系统有多大QPS？系统到底怎么抗住高并发的？](https://mp.weixin.qq.com/s?__biz=MzU0OTk3ODQ3Ng==&mid=2247484908&idx=1&sn=6acc6ff3ce5e2ca1d0c2639868356a5e&chksm=fba6edefccd164f92d15faab6b8f77e4118c299ea5b1c366ac2db2aad9f12c761ef051355600&mpshare=1&scene=1&srcid=0608rMH6pNVzMB7wHy5caCrN%23rd)
- [面对BAT大厂的竞争对手时，小公司Java工程师是如何败北的？](https://mp.weixin.qq.com/s?__biz=MzU0OTk3ODQ3Ng==&mid=2247484786&idx=1&sn=be07d63f36ee97031031dc455c03e3ca&chksm=fba6ed71ccd164677ef4e94ad64409783ec4a35d0cf8cfc2f2672a58099a382a496db2abf313&mpshare=1&scene=1&srcid=0608FUyrpWhHO2WyA36i9JK9%23rd)
- [我一连面试了十个Java岗，统统石沉大海！](https://mp.weixin.qq.com/s?__biz=MzU0OTk3ODQ3Ng==&mid=2247484590&idx=1&sn=9d63dd0c4ab9150f6ac32f327d349d3b&chksm=fba6ecadccd165bb3c96ebd792d677ce25614f1cf48dbbe255534c149fe447c88761077f16b4&mpshare=1&scene=1&srcid=0608MowbddtGYWq6Fa26nPIJ%23rd)
- [面试最让你手足无措的一个问题：你的系统如何支撑高并发？](https://mp.weixin.qq.com/s?__biz=MzU0OTk3ODQ3Ng==&mid=2247484429&idx=1&sn=d8038c21ecd733b8bb7ff784014243f9&chksm=fba6ec0eccd165189e92a294ab2b7cd6796982c188befe05c27f4e96ae5cd39f2baf436cf37d&mpshare=1&scene=1&srcid=0608ttwG3fBdBUt7pdxL5IhX%23rd)
- [【斩获7枚offer，入职阿里平台事业部】横扫阿里、美团、京东、 去哪儿之后，我写下了这篇面经！](https://mp.weixin.qq.com/s?__biz=MzU0OTk3ODQ3Ng==&mid=2247485090&idx=1&sn=5502672d9bf52551038b911d7ab623b9&chksm=fba6eea1ccd167b73a542b76dad423da21a2b452f768aac996cb50eeac1adc5d4978afe762ce&mpshare=1&scene=1&srcid=0608mo3eKwh686hXNzvRQfEB%23rd)
- [三年努力，梦归阿里！](https://mp.weixin.qq.com/s?__biz=MzU0OTk3ODQ3Ng==&mid=2247485010&idx=1&sn=cd158d8358a0758fa81af094d58e2ea2&chksm=fba6ee51ccd1674753d77c8ab2a522cd8e32373b0a104eb9ecd6008cd12b6457eaade77e0514&mpshare=1&scene=1&srcid=0608LIOSiYzoUmlBHC4ZhnnZ%23rd)
- [二本出身、逆袭网易、一路孤独、一路狂欢！](https://mp.weixin.qq.com/s?__biz=MzU0OTk3ODQ3Ng==&mid=2247484844&idx=1&sn=cfa78df2943567269909f87217fa25c8&chksm=fba6edafccd164b9f6c22162a6386734010aeee9a084de720dacbb72d58bd1c20c0f961f5315&mpshare=1&scene=1&srcid=0608Ufv5zYZu66XnNn89WYEU%23rd)
- [小公司出身的我，是如何拿下知名独角兽公司offer的？](https://mp.weixin.qq.com/s?__biz=MzU0OTk3ODQ3Ng==&mid=2247484813&idx=1&sn=4c9a43e51e1cf114efcf938e60ad58fd&chksm=fba6ed8eccd16498840a715659b8a29cf3368d28cf67c6fb27255277abe63421bca9ceb2cae7&mpshare=1&scene=1&srcid=06083zOsdotiVg1juwK3MYxZ%23rd)
- [【行走的Offer收割机】记一位朋友斩获BAT技术专家Offer的面试经历](https://mp.weixin.qq.com/s?__biz=MzU0OTk3ODQ3Ng==&mid=2247484170&idx=1&sn=6c178884c1c5399e37562b9dc66cff6c&chksm=fba6eb09ccd1621ff8821b37f12d6df8a1d269ddc95ad10c0a4e71a3bf0017952bf19978d8ec&mpshare=1&scene=1&srcid=0608ezj6dEIln43Sl011MZz3%23rd)




### 	[分布式消息队列](https://github.com/wulimax/reactApp/tree/master/docs/DistributedMessageQueue)

### 	[分布式搜索引擎](https://github.com/wulimax/reactApp/blob/master/docs/Elasticsearch/README.md)

### 	[分布式缓存](https://github.com/wulimax/reactApp/blob/master/docs/DistributedCache/README.md) 

### 	[分库分表](https://github.com/wulimax/reactApp/tree/master/docs/DatabaseSharding)

### 	[分布式锁](/docs/DistributedLock/README.md)

### 	[分布式事务](https://github.com/wulimax/reactApp/blob/master/docs/DistributedTransaction/README.md)

### 	[限流降级](https://github.com/wulimax/reactApp/blob/master/docs/RateLimit/README.md)

### 公众号:石杉的架构笔记

如果大家想要实时关注我更新的文章以及分享的干货的话，可以关注我的公众号。

![我的公众号](https://github.com/wulimax/reactApp/blob/master/docs/PublicImage/shishan100.jpg)


### 关于转载
本仓库所有文章系石杉的架构笔记原创文章，如需转载，请联系公众号石杉的架构笔记获取授权，否则将追究法律责任。










