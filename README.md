# reference

参考资料

## 工具

- [git book](https://git-scm.com/book/zh/v2)
- [Tcpdump Examples](https://hackertarget.com/tcpdump-examples/)
- [TCPDump Capture HTTP GET/POST requests
](https://www.middlewareinventory.com/blog/tcpdump-capture-http-get-post-requests-apache-weblogic-websphere/#How_to_Filter_HTTP_User_Agents)

## 编程语言

### C++
- [C++11新特性](http://c.biancheng.net/cplus/11/)

## 操作系统与网络

- [请你谈谈关于IO同步、异步、阻塞、非阻塞的区别](https://mp.weixin.qq.com/s/UEPXpQBJgSk08bg96wy96Q)
- [I/O与Netty原理精讲](https://mp.weixin.qq.com/s/K9Oyn0cbwqVCh1j3N5bd_w)

## 大数据

### 架构

- [进击的巨人之MPP数据库](https://mp.weixin.qq.com/s/3hEXj3craLXyXycnPGWFEw)
- [Shared Nothing v.s. Shared Disk Architectures: An Independent View](http://www.benstopford.com/2009/11/24/understanding-the-shared-nothing-architecture/)
- [OLAP 核心知识点](https://mp.weixin.qq.com/s/QUTuk7Oc9-YXxCwtbBSYoA)
- [李飞飞：云原生分布式数据库面临哪些机遇与挑战？](https://mp.weixin.qq.com/s/zHBUEWCpPOgz3pvLAu32BQ)
- [我们为什么放弃 MongoDB 和 MySQL，选择 TiDB](https://mp.weixin.qq.com/s/FuZZk_jnaipqA4-SMMvNLQ)：很好的关于技术选型的文章。
- [一个PhD的论文笔记](https://github.com/hustnn/papers-notebook)
- [开源关系型数据库架构](https://my.oschina.net/taogang/blog/4953500)
- [浅析分布式计算模型的发展变化](https://mp.weixin.qq.com/s/why798vQyRviSrDp75wLrg)

### 数据结构与算法

- [LSM-Tree](https://cloud.tencent.com/developer/article/1441835)
- [跳表](https://mp.weixin.qq.com/s?__biz=MzAxMzE4MDI0NQ==&mid=2650336541&idx=1&sn=641646d7ebb267f59fd2d39c9c143411&chksm=83aac127b4dd4831a6ed788675455e88975f5ac64813108e033d47c6fbe03f2090d171f21b00&scene=21#wechat_redirect)

### 存储引擎

- [数据库选型时必知的存储引擎基础](https://mp.weixin.qq.com/s/8KV-Iyyx9JiiTVJPV7gNug)
- [掌握了LSM架构，你就掌握了90%的分布式数据库](https://github.com/cloudnativecube/reference/tree/master/%E5%88%86%E5%B8%83%E5%BC%8F%E6%95%B0%E6%8D%AE%E5%BA%93)
- [Why we built CockroachDB on top of RocksDB](https://www.cockroachlabs.com/blog/cockroachdb-on-rocksd/)

### hadoop

### yarn
- [让你彻底搞明白YARN资源分配](https://blog.csdn.net/ChinaPoison/article/details/111028535)

### spark

#### spark基础

- [B站视频-Spark从零到精通完整版](https://www.bilibili.com/video/BV1ui4y1V7Cf?p=63)：需要看的基础章节包括：概述、集群搭建、入门、深入RDD、RDD的分区、RDD的缓存、Spark原理（SparkSQL可以后续再看）
- [spark知识点总结](https://zhuanlan.zhihu.com/p/71270044)
- [马殿军的源码分析](https://github.com/marsno1/notes/tree/master/Spark/%E6%BA%90%E7%A0%81%E5%88%86%E6%9E%90)
- [Spark源码阅读](https://masterwangzx.com/categories/#Spark)
- [SparkSQL Hive ThriftServer 源码解析：SparkSQLCLIService](https://mr-dai.github.io/sparksql_hive_thriftserver_source_2/)
- [Spark CommitCoordinator 保证数据一致性](https://zhuanlan.zhihu.com/p/45351972)
- [Data Source V2 API in Spark 3.0](http://blog.madhukaraphatak.com/categories/datasource-v2-spark-three/)
- [一文理解 Apache Spark DataSource V2 诞生背景及入门实战](https://zhuanlan.zhihu.com/p/83006243)
- [Spark内存管理详解](https://mp.weixin.qq.com/s/t4qO6HKOu3XaIgLGcTtLJw)
- [如何实现Spark on Kubernetes？](https://developer.aliyun.com/article/774585)
- [Spark on K8S 在有赞的实践](https://mp.weixin.qq.com/s/dcymNAco7P4IzuXA4pHezg)
- [探索Spark Tungsten的秘密](https://github.com/hustnn/TungstenSecret)
- [Spark性能优化指南——基础篇](https://mp.weixin.qq.com/s/lcCvp1s5BYKpGSO__SAfbA)
- [Spark性能优化指南——高级篇](https://mp.weixin.qq.com/s/KIoE3ev7XgGGH05kjCX_zQ)
- [Spark常见问题汇总](https://blog.csdn.net/peace1213/article/details/97942856)
- [The Internals Online Books](https://books.japila.pl/)
  - [The Internals of Apache Spark](https://books.japila.pl/apache-spark-internals/overview/)
  - [The Internals of Spark SQL](https://jaceklaskowski.github.io/mastering-spark-sql-book/spark-sql/)

#### hive迁移spark

- [Hive SQL迁移Spark SQL在滴滴的实践](https://mp.weixin.qq.com/s/yiqgPqM7nnNlJ1zCp6blTQ)
- [SparkSQL 在有赞的实践](https://mp.weixin.qq.com/s/Gs67ZUjlpgmo5WednjJ3lQ)
- [SparkSQL在有赞大数据的实践（二）](https://mp.weixin.qq.com/s/r9S93ZHWzQLPlN_ixqHAVQ)
- [Spark 2.3 无缝升级到 3.0 在唯品会的实践](https://mp.weixin.qq.com/s/pf-MbjLeeVV2Ii7wNuRXIg)

#### Remote Shuffle Service

- [京东Spark自研Remote Shuffle Service在大促中的应用实践](https://mp.weixin.qq.com/s/yELhZ1X-VG5YxR6ya32rAQ)
- [降本增效利器！趣头条Spark Remote Shuffle Service最佳实践](https://mp.weixin.qq.com/s/KRD-czsKJHQsuyNXMriGWQ)
- [Magnet: A scalable and performant shuffle architecture for Apache Spark](https://engineering.linkedin.com/blog/2020/introducing-magnet)
- [Cosco: An Efficient Facebook-Scale Shuffle Service](https://bestoreo.github.io/post/cosco/cosco/)
- [github: uber rss](https://github.com/uber/RemoteShuffleService)
- [github: linkedin magnet](https://github.com/linkedin/spark/tree/magnet-upstream)
- [SPARK-31924: Create remote shuffle service reference implementation](https://issues.apache.org/jira/browse/SPARK-31924)
- [SPARK-25299: Use remote storage for persisting shuffle data](https://issues.apache.org/jira/browse/SPARK-25299)
- [SPARK-30602: Support push-based shuffle to improve shuffle efficiency](https://issues.apache.org/jira/browse/SPARK-30602)

### hive

- [hive.md](https://github.com/cloudnativecube/reference/blob/master/hive.md)

### hbase

### clickhouse

- [ClickHouse使用指南](https://blog.alexanderliu.top/posts/clickhouse-user-guide.html)
- [马殿军的源码分析](https://github.com/marsno1/notes/tree/master/ClickHouse)
- [ClickHouse和他的朋友们](https://bohutang.me/archives/)
- [ClickHouse
Query Execution Pipeline](https://presentations.clickhouse.tech/meetup24/5.%20Clickhouse%20query%20execution%20pipeline%20changes/)
- [ClickHouse新特性Live View体验](https://blog.csdn.net/jiangshouzhuang/article/details/104981269)
- [知乎专栏：Clickhouse最佳实战](https://www.zhihu.com/column/c_1267228880110850048)
- [clickhouse分析：zookeeper数据存储](https://blog.csdn.net/iceyung/article/details/104060187)
- [DorisDB VS ClickHouse 视频](https://www.bilibili.com/video/BV13v411s7sh?from=search&seid=1587356354978598948)
- [看云上ClickHouse如何做计算存储分离](https://mp.weixin.qq.com/s/EMOO2YhgjncebyMPl9azZw)
- [云数据库ClickHouse资源隔离-弹性资源队列](https://developer.aliyun.com/article/780376?utm_content=g_1000223973)
- [云数据库ClickHouse二级索引-最佳实践](https://developer.aliyun.com/article/781180?spm=a2c6h.12873581.0.dArticle781180.35a1802f9jXIdT)
- [ClickHouse如何实现极致存储压缩率和查询性能？](https://mp.weixin.qq.com/s/UDps126LR5kMAxTk65ozOg)
- [四两拨千斤：小巧新秀ClickHouse如何完美支撑史上最强双十一？](https://mp.weixin.qq.com/s/Wwu_SYcCwjen1je_iq6paw)

## 云原生数仓

### snowflake

- [Snowflake: The Good, The Bad and The Ugly](https://0x0fff.com/snowflake-the-good-the-bad-and-the-ugly/)
- [snowflake-security](https://community.snowflake.com/s/snowflake-security)
- [https://looker.com/databases/snowflake](https://looker.com/databases/snowflake)
- [A Snowflake deep dive](https://hhhypergrowth.com/a-snowflake-deep-dive/)
- [市值700亿美金-云上数据仓库snowflake成功之道](https://developer.aliyun.com/live/245723?spm=a2c6h.12873639.0.0.464bfa8bRIMLYh)
- [从snowflake上市漫谈云数仓
](https://zhuanlan.zhihu.com/p/261389683)
- [The Snowflake Elastic Data Warehouse](https://dl.acm.org/doi/pdf/10.1145/2882903.2903741) 译文：[新一代数据仓库：Snowflake 弹性数仓介绍](https://mp.weixin.qq.com/s/BUPh8B0WA_bXQTsGoZjxOg)
- [snowflake官方文档：Data Loading](https://docs.snowflake.com/en/user-guide/data-load-overview.html)
