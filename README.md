本仓库的名字 **read the fucking 42** 来源于两部分的组成：

1. Google 搜索：[the answer to life the universe and everything](https://www.google.com/search?newwindow=1&sxsrf=ALeKk02LidI--os2Bui67zR_qwjYgUtgdQ%3A1606834389546&ei=1VjGX_jYIIH_wAOMrIboCg&q=the+answer+to+life+the+universe+and+everything&oq=the+answer+to+life+the+universe+and+everything&gs_lcp=CgZwc3ktYWIQAzIHCCMQyQMQJzICCAAyAggAMgIIADICCAAyAggAMgIIADICCAAyAggAMgIIADoECAAQR1D4HlinJmDDLWgAcAJ4AIAB0QGIAeIJkgEFMC42LjGYAQCgAQGqAQdnd3Mtd2l6yAEIwAEB&sclient=psy-ab&ved=0ahUKEwi4l4HIhK3tAhWBP3AKHQyWAa0Q4dUDCA0&uact=5) 的结果为 42。

    `42，是道格拉斯·亚当斯所作的小说《银河系漫游指南》中“生命、宇宙以及任何事情的终极答案”的答案`
2. SpaceX 有两艘可操作的无人驾驶着陆船，一艘名字为“当然我还爱你”（[Of Course I Still Love You](https://spacexfleet.com/of-course-i-still-love-you)），另一艘名字为“请阅读说明书”号（[Just Read the Instructions](https://www.space.com/28445-spacex-elon-musk-drone-ships-names.html)）

**read the fucking 42** 代表：

- [read the fucking manual](https://en.wikipedia.org/wiki/RTFM)
- read the fucking source code
- read the fucking article 
- read the fucking wiki
- read the fucking book

欢迎大家一起建设此仓库 :-)

收录文章标准：

- 原则上收录的文章一定一定**要有参考资料**，比如**官网文档，wikipedia**相关条目介绍等等
- 原则上收录的文章一定一定**不要有表情包**

---

# 计算机网络与协议
- [为什么 TCP 建立连接需要三次握手 - Why’s THE Design](https://draveness.me/whys-the-design-tcp-three-way-handshake/)  
  RFC官方文档的解读要比用打电话打比方的解读权威精准

- [TCP三次握手和四次挥手](https://github.com/sunweiguo/Http/issues/5)

- [为什么 TCP 协议有粘包问题 - Why’s THE Design](https://draveness.me/whys-the-design-tcp-message-frame/)

- [为什么 TCP 协议有 TIME_WAIT 状态 - Why’s THE Design](https://draveness.me/whys-the-design-tcp-time-wait/)

- [线上大量 CLOSE_WAIT 原因排查](https://cloud.tencent.com/developer/article/1381359)   
    //netstat -na | awk '/^tcp/ {++S[$NF]} END {for(a in S) print a, S[a]}'

- [使用 WireShark 分析 TCP/IP 三次握手 和 四次挥手](https://www.cnblogs.com/bylijian/p/8565601.html)  
  
- [从输入 URL 到页面加载完成的过程中都发生了什么事情？ - 百度 FEX](http://fex.baidu.com/blog/2014/05/what-happen/)    

- [从 URL 输入到页面展现到底发生什么？](https://github.com/ljianshu/Blog/issues/24)
  
- [当···时发生了什么？- what-happens-when-zh_CN](https://github.com/skyline75489/what-happens-when-zh_CN)    

- [聊聊 TCP 长连接和心跳那些事 - 徐靖峰](https://www.cnkirito.moe/tcp-talk/)
  
- [计算机网络_传输层 - CyC2018](https://github.com/CyC2018/CS-Notes/blob/master/notes/%E8%AE%A1%E7%AE%97%E6%9C%BA%E7%BD%91%E7%BB%9C%20-%20%E4%BC%A0%E8%BE%93%E5%B1%82.md)      
    
---

# 操作系统

- [Linux 常用命令总结 - 手册制作: 雪松 ](https://github.com/liquanzhou/ops_doc/blob/master/shell%E5%AE%9E%E4%BE%8B%E6%89%8B%E5%86%8C.sh)  
    运维工程师的总结

---

# Java

## Java 基础

- [《书名：《计算机程序的思维逻辑》- 作者：马俊昌》](https://www.cnblogs.com/swiftma/p/5631311.html)  
    点击链可以免费阅读。微信读书也可读
    
- [Java中 SPI 机制](https://juejin.cn/post/6844903679431016456)

## 集合框架

欢迎大家补充 相关技术文章   TODO

- [Java 8 系列之重新认识 HashMap - 美团点评技术团队](https://web.archive.org/web/20161227072247/http://tech.meituan.com/java-hashmap.html)

- [疫苗：Java HashMap 的死循环 - coolshell](https://coolshell.cn/articles/9606.html)

## Java 并发与多线程

- 《书名：Java并发编程的艺术_作者：方腾飞　魏鹏　程晓明》  
 方腾飞，并发编程网创始人。微信读书可读

- 《书名：Java并发编程之美_作者：翟陆续，薛宾田》  
    微信读书可读

- 《书名：Java并发实现原理：JDK源码剖析_作者：余春龙》  
    微信读书可读

- 《Java Concurrency In Practice_作者：Brian Göetz、Doug Lea 等》  
    个人建议，不要读中文版，翻译得太差，让人怀疑人生 :-)

- [Java并发性和多线程介绍目录 - Java并发编程网翻译](http://ifeve.com/java-concurrency-thread-directory/)

- [阿里巴巴 《Java 开发手册》编程规约 (六) 并发处理](https://developer.aliyun.com/special/tech-java)  
    点击链接可读，微信读书也可读

### synchronized 

- [不可不说的Java“锁”事 - 美团技术团队](https://tech.meituan.com/2018/11/15/java-lock.html)

- [synchronized 实现原理 - 小米信息技术部团队](https://xiaomi-info.github.io/2020/03/24/synchronized/)

- [synchronized 原理及其应用](https://juejin.cn/post/6844904114061590535)

- [关键字: synchronized 详解](https://www.pdai.tech/md/java/thread/java-thread-x-key-synchronized.html)

- [死磕 Synchronized 底层实现](https://github.com/farmerjohngit/myblog/issues/12)

### ReentrantLock

- [从ReentrantLock的实现看AQS的原理及应用 - 美团技术团队](https://tech.meituan.com/2019/12/05/aqs-theory-and-apply.html)

### 线程池

- [Java线程池实现原理及其在美团业务中的实践 - 美团技术团队](https://tech.meituan.com/2020/04/02/java-pooling-pratice-in-meituan.html)

## NIO

- [Java NIO浅析 - 美团技术团队](https://tech.meituan.com/2016/11/04/nio.html)

## JVM 虚拟机

- 《书名：深入理解Java虚拟机：JVM高级特性与最佳实践（第3版）_作者：周志明》   
    微信读书可读
  
- [Java Garbage Collection Basics - Oracle 官方文档](https://www.oracle.com/webfolder/technetwork/tutorials/obe/java/gc01/index.html)  
    Time to Complete，Approximately 1 hour

- [监控调优故障排除_命令行工具_GUI 工具 - 官方文档](https://docs.oracle.com/javase/8/docs/technotes/tools/windows/toc.html)    
    javap、jps、jmc、jvisualvm、jstat、jinfo、jstack、jmap等等

- [VM Options Explorer - OpenJDK8 HotSpot](https://chriswhocodes.com/hotspot_options_jdk8.html)  
    各种版本 OpenJDK 虚拟机参数  
    
---

# MySQL

- [英文：How does a relational database work](http://coding-geek.com/how-databases-work/)

- [中文翻译：How does a relational database work](https://web.archive.org/web/20190103130821/http://blog.jobbole.com/100349/)
    原标题：如果有人问你数据库的原理，叫他看这篇文章  

- [Innodb中的事务隔离级别和锁的关系 - 美团技术团队](https://tech.meituan.com/2014/08/20/innodb-lock.html)

- [MySQL索引原理及慢查询优化 - 美团技术团队](https://tech.meituan.com/2014/06/30/mysql-index.html)

- [阿里巴巴 《Java 开发手册》五、MySQL 数据库](https://developer.aliyun.com/special/tech-java)  
    点击链接可读，微信读书也可读

---

# Redis  

- 《书名：Redis设计与实现_作者：黄健宏》  
     微信读书可读

- 《书名：Redis 深度历险：核心原理与应用实践_作者: 钱文品》

- [Redis - documentation 官方文档](https://redis.io/documentation)  
    data types、transactions、Persistence（持久化RDB、AOF）、Distributed locks 等等

- [7 Redis Worst Practices 官方博文](https://redislabs.com/blog/7-redis-worst-practices/)
    7 个最糟糕的 Redis 用法。比如，为什么生产环境不让用 keys 命令？

- [缓存 - Advanced Java](https://github.com/doocs/advanced-java/blob/main/README.md#%E7%BC%93%E5%AD%98)  
    缓存与数据库双写不一致，缓存雪崩、缓存穿透、缓存击穿，Redis 持久化，Redis 过期策略、主从、集群、哨兵 等等
    
- [缓存那些事 - 美团技术团队](https://tech.meituan.com/2017/03/17/cache-about.html)

- [缓存更新的套路 - CoolShell](https://coolshell.cn/articles/17416.html)

- [缓存架构设计细节二三事 - 58沈剑](https://www.w3cschool.cn/architectroad/architectroad-cache-architecture-design.html)
      
- [LRU 缓存机制 - LeetCode 146](https://leetcode-cn.com/problems/lru-cache/)

- 分布式锁相关，请在本页面 command + F 搜索关键字：分布式锁      

---

# 分布式

- [分布式 - Cyc2018](https://github.com/CyC2018/CS-Notes/blob/master/notes/%E5%88%86%E5%B8%83%E5%BC%8F.md)  
    分布式锁、分布式事务、CAP、BASE、Paxos、Raft

- [分布式系统互斥性与幂等性问题的分析与解决 - 美团技术团队](https://tech.meituan.com/2016/09/29/distributed-system-mutually-exclusive-idempotence-cerberus-gtis.html)  
  
- [一致性哈希算法的理解与实践](https://github.com/Yikun/yikun.github.com/issues/53)  

- [图解一致性哈希算法](https://segmentfault.com/a/1190000021199728)

- [序列化和反序列化 - 美团点评技术团队](https://tech.meituan.com/2015/02/26/serialization-vs-deserialization.html)

- [Kryo 和 FST 序列化 - Dubbo 官方文档](http://dubbo.apache.org/zh/docs/v2.7/user/serialization/)

## 分布式会话与单点登录SSO

### 分布式会话

- [集群部署时的分布式 Session 如何实现？](https://github.com/doocs/advanced-java/blob/main/docs/distributed-system/distributed-session.md)

- [分布式 Session](https://github.com/wangzhiwubigdata/God-Of-BigData/blob/master/%E5%88%86%E5%B8%83%E5%BC%8F%E7%90%86%E8%AE%BA/%E5%88%86%E5%B8%83%E5%BC%8F%E7%B3%BB%E7%BB%9F%E7%9A%84%E4%B8%80%E4%BA%9B%E5%9F%BA%E6%9C%AC%E6%A6%82%E5%BF%B5.md#%E4%B8%89%E5%88%86%E5%B8%83%E5%BC%8F-session)

- [How to manage sessions in a distributed application](https://stackoverflow.com/questions/32688648/how-to-manage-sessions-in-a-distributed-application)

- [Spring Session](https://spring.io/projects/spring-session)

### SSO（单点登录）
- [全面介绍SSO（单点登录）](https://juejin.cn/post/6844904009820536840)

- 其他：[理解OAuth 2.0](https://www.ruanyifeng.com/blog/2014/05/oauth_2_0.html)

## 分布式搜索引擎 - Elasticsearch

## 分布式文件系统 - FastDFS - 阿里OSS

## 消息队列

- [消息队列设计精要](https://tech.meituan.com/2016/07/01/mq-design.html)  
  
### RabbitMQ
欢迎大家补充 相关技术文章   TODO

### Kafka
欢迎大家补充 相关技术文章   TODO

### RocketMQ
欢迎大家补充 相关技术文章   TODO

## 分布式锁

- [Distributed locks with Redis - Redis 官网](https://redis.io/topics/distlock)  

- [Redis_分布式锁原理](https://github.com/heibaiying/Full-Stack-Notes/blob/master/notes/Redis_%E5%88%86%E5%B8%83%E5%BC%8F%E9%94%81%E5%8E%9F%E7%90%86.md)

- [distributed-lock-redis-vs-zookeeper - advanced-java](https://github.com/doocs/advanced-java/blob/main/docs/distributed-system/distributed-lock-redis-vs-zookeeper.md)  
    一般实现分布式锁都有哪些方式？使用 Redis 如何设计分布式锁？使用 zk 来设计分布式锁可以吗？这两种分布式锁的实现方式哪种效率比较高？

- [Redlock分布式锁](https://github.com/Snailclimb/JavaGuide/blob/master/docs/database/Redis/Redlock%E5%88%86%E5%B8%83%E5%BC%8F%E9%94%81.md)  
    这篇文章主要是对 Redis 官方网站刊登的 Distributed locks with Redis 部分内容的总结和翻译。

- [如何做可靠的分布式锁，Redlock真的可行么 - JavaGuide](https://github.com/Snailclimb/JavaGuide/blob/master/docs/database/Redis/%E5%A6%82%E4%BD%95%E5%81%9A%E5%8F%AF%E9%9D%A0%E7%9A%84%E5%88%86%E5%B8%83%E5%BC%8F%E9%94%81%EF%BC%8CRedlock%E7%9C%9F%E7%9A%84%E5%8F%AF%E8%A1%8C%E4%B9%88.md)  
    本文是对 Martin Kleppmann 的文章 How to do distributed locking 部分内容的翻译和总结  

- [分布式锁的实现及原理](https://github.com/jinhailang/blog/issues/47)  
    基于 Etcd 与 基于 Redis 的实现方案对比  

## 读写分离、分库分表

欢迎大家补充 相关技术文章   TODO

## 分布式 ID 生成
- [Leaf_美团点评分布式ID生成系统](https://tech.meituan.com/2017/04/21/mt-leaf.html)  

- [分布式 ID 基本原理](https://github.com/dunwu/blog/blob/master/source/_posts/theory/distributed-id.md)

- [分布式Unique ID的生成方法一览 - 江南白衣](https://web.archive.org/web/20191024010345/http://calvin1978.blogcn.com/articles/uuid.html)  

- [如何设计一个分布式ID生成器(Distributed ID Generator)，并保证ID按时间粗略有序？](https://github.com/soulmachine/system-design/blob/master/cn/distributed-id-generator.md)

- [细聊分布式ID生成方法 - 【58沈剑架构系列】](https://www.cnblogs.com/codeon/p/6415273.html)

## 分布式事务和数据一致性

- [分布式事务基本原理](https://github.com/dunwu/blog/blob/master/source/_posts/theory/distributed-transaction.md)  
    本地事务、分布式事务、CAP 和 BASE、2PC、3PC、TCC、本地消息表、MQ、SAGA

- [分布式事务](https://github.com/CyC2018/CS-Notes/blob/master/notes/%E5%88%86%E5%B8%83%E5%BC%8F.md#%E4%BA%8C%E5%88%86%E5%B8%83%E5%BC%8F%E4%BA%8B%E5%8A%A1)  
  
- [分布式事务了解吗？你们是如何解决分布式事务问题的？](https://github.com/doocs/advanced-java/blob/main/docs/distributed-system/distributed-transaction.md)
  
- [分布式事务](https://github.com/kailbin/blog/issues/12)  

## 分布式接口幂等性

- [关于幂等的理解](https://github.com/lq920320/blogs/issues/24)

- [幂等设计](https://github.com/samjustin8231/JavaGuide/blob/master/%E5%88%86%E5%B8%83%E5%BC%8F/%E5%B9%82%E7%AD%89%E8%AE%BE%E8%AE%A1.md)  
  
- [分布式服务接口的幂等性如何设计（比如不能重复扣款）？](https://github.com/doocs/advanced-java/blob/main/docs/distributed-system/distributed-system-idempotency.md)

## 分布式限流

- [来谈谈限流-从概念到实现](https://github.com/farmerjohngit/myblog/issues/18)  

- [来谈谈限流-RateLimiter源码分析](https://github.com/farmerjohngit/myblog/issues/19)

- [限流算法: 令牌桶(token bucket) vs 漏桶(leak bucket)](https://github.com/isayme/blog/issues/27)  

- [限流](http://dylanvivi.github.io/posts/rate-limiter.html)

- [常用限流降级组件对比 - alibaba Sentinel](https://github.com/alibaba/Sentinel/wiki/%E5%B8%B8%E7%94%A8%E9%99%90%E6%B5%81%E9%99%8D%E7%BA%A7%E7%BB%84%E4%BB%B6%E5%AF%B9%E6%AF%94)

---

# 微服务

欢迎大家补充 相关技术文章   TODO

SpringCloud

Netty

ZooKeeper

## Dubbo

- [Dubbo 中的扩展点加载机制 - Dubbo 官网](http://dubbo.apache.org/zh/docs/v2.7/dev/spi/)    
    Dubbo 的扩展点加载从 JDK 标准的 SPI (Service Provider Interface) 扩展点发现机制加强而来。

---

# 系统设计

- [搞定面试中的系统设计题](https://jiajunhuang.com/articles/2019_04_29-system_design.md.html)

- [system_design_primer - 掘金翻译计划](https://github.com/donnemartin/system-design-primer/blob/master/README-zh-Hans.md)  

- [系统设计面试题精选](https://soulmachine.gitbooks.io/system-design/content/cn/)

- [秒杀](https://github.com/gzc426/Java-Interview/blob/master/%E9%A1%B9%E7%9B%AE%E6%8E%A8%E8%8D%90/%E7%A7%92%E6%9D%80.md)

- [秒杀系统架构分析与实战](https://github.com/hackjutsu/Hackjutsu/blob/master/source/_posts/%E7%A7%92%E6%9D%80%E7%B3%BB%E7%BB%9F%E6%9E%B6%E6%9E%84%E5%88%86%E6%9E%90%E4%B8%8E%E5%AE%9E%E6%88%98.md)
- [如何避免电商秒杀中出现的超卖超买现象](https://github.com/chenqingspring/blog/issues/1)
- [一般电商网站中，下单和减库存是怎么设计的 - v2ex](https://www.v2ex.com/t/703857)

