[![返回目录](https://user-images.githubusercontent.com/5803001/38079637-ff0abcf0-3371-11e8-9b76-ad651620afc7.jpg)](https://github.com/wx-chevalier/Awesome-Lists)

# Distributed Transaction List

* [Why you should pick strong consistency, whenever possible](https://parg.co/U8P)

- [Distributed transactions and why you should care](https://towardsdatascience.com/distributed-transactions-and-why-you-should-care-116b6da8d72): If my product succeeds will this eventual-consistency thing come back to haunt me?

* [使用 Redis 实现分布式锁](http://blog.jobbole.com/95211/)

- [关于分布式事务、两阶段提交协议、三阶提交协议](http://www.hollischuang.com/archives/681)

- [深入理解分布式系统的 2PC 和 3PC](http://www.hollischuang.com/archives/1580)

- [分布式系统事务一致性解决方案](http://www.infoq.com/cn/articles/solution-of-distributed-system-transaction-consistency)

- [分布式系统的事务处理 ](http://mp.weixin.qq.com/s?__biz=MzA4NDc2MDQ1Nw==&mid=2650238031&idx=1&sn=d7ba7844f15d587c83906aedd073748a&scene=0#wechat_redirect)

- [分布式事务 2PC && 3PC](http://int64.me/2016/%E5%88%86%E5%B8%83%E5%BC%8F%E4%BA%8B%E5%8A%A12PC%20&&%203PC.html)

# 多阶段提交

* [分布式协议之两阶段提交协议(2PC)和改进三阶段提交协议(3PC)](http://www.mamicode.com/info-detail-890945.html)

* [关于分布式事务、两阶段提交、一阶段提交、Best Efforts 1PC 模式和事务补偿机制的研究](http://blog.csdn.net/bluishglc/article/details/7612811)

* [两阶段提交协议与三阶段提交协议](http://www.tuicool.com/articles/mARV3u)

# 分布式锁

* [高并发下本地锁+分布式锁](https://adamswanglin.github.io/wllock/)

* [基于 Consul 的分布式锁实现](http://blog.didispace.com/spring-cloud-consul-lock-and-semphore/)：  我们在构建分布式系统的时候，经常需要控制对共享资源的互斥访问。这个时候我们就涉及到分布式锁(也称为全局锁)的实现，基于目前的各种工具，我们已经有了大量的实现方式，比如：基于 Redis 的实现、基于 Zookeeper 的实现。本文将介绍一种基于 Consul 的 Key/Value 存储来实现分布式锁以及信号量的方法。

# 分布式 ID

* [分布式 ID 生成系统怎么做？](http://mp.weixin.qq.com/s/vurewakh7jINbmgKWR8rTw): 在分布式系统中，经常需要对大量的数据、消息、http 请求等进行唯一标识，例如：对于分布式系统，服务间相互调用需要唯一标识，调用链路分析的时候需要使用这个唯一标识。

- [五分钟了解分布式 ID 生成方案](http://mp.weixin.qq.com/s?__biz=MzA5ODM0NjA3NA==&mid=2651209088&idx=1&sn=640af6452e8644e65c5c5985eb405358&scene=4#wechat_redirect)

- [2017-Leaf—— 美团点评分布式 ID 生成系统](http://tech.meituan.com/MT_Leaf.html)：在复杂分布式系统中，往往需要对大量的数据和消息进行唯一标识。如在美团点评的金融、支付、餐饮、酒店、猫眼电影等产品的系统中，数据日渐增长，对数据分库分表后需要有一个唯一 ID 来标识一条数据或消息，数据库的自增 ID 显然不能满足需求；特别一点的如订单、骑手、优惠券也都需要有唯一 ID 做标识。此时一个能够生成全局唯一 ID 的系统是非常必要的。。

## Twitter-Snowflake

* [Twitter-Snowflake，64 位自增 ID 算法详解](http://www.lanindex.com/twitter-snowflake%EF%BC%8C64%E4%BD%8D%E8%87%AA%E5%A2%9Eid%E7%AE%97%E6%B3%95%E8%AF%A6%E8%A7%A3/)

* [微信序列号生成器架构设计及演变](http://h2ex.com/1163)
