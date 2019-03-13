## Spring事务管理 JTA

### 分布式事务的困难

单一数据源借助数据库本地事务管理

分布式事务管理：不能借助本地事务完成



需要一个全局事务协调管理器

### XA规范 两阶段提交

XA规范：

![image-20190301095254021](/Users/shenyi/Project/learning/JavaGuide/Java高级网易直播/img/image-20190301095254021.png)

### JTA是什么



javax.transaction-api

面向TM、RM提供商的API：transactionManager，Transaction，XARsource，Xid



spring提供了很好的集成，



Atomikos学习链接

https://www.atomikos.com