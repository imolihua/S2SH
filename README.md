# S2SH
Struts2,Hibernate,Spring三大框架的整合总是很麻烦，在此提供一个已经整合好三大框架的包，可以直接下载导入Myeclipse使用，项目基于Maven做依赖管理。

其中包含的内容如下：
  
1.Struts2.3.16.3,Hibernate4.3.5,Spring4.0.4三大框架的整合；

2.前端框架集成了Bootstrap3.3.5，Jquery1.12.3,集成了Bootstrap插件Bootgrid数据表格实现分页，使用Bootstrap的datetimepicker插件实现日期时间选择；

3.数据库使用Mysql中自带的sakila数据库，使用前，请将resource中的applicationContext.xml中的数据库密码设置为自己的；

4.实现了sakila中的单表的增删改查和跨表查询，跨表查询包括了hibernate的1-N和1-1双向映射；

5.集成了作业自动调度框架Quartz 2.2.2实现作业调度；

6.json插件使用Struts2自带的json插件；

7.包含了一个文件上传的功能和数据表导出为Excel下载的功能，使用POI实现；

8.包含了带验证码的登录功能以及登录验证的拦截器；

9.整个包可直接导入Myeclipse继续编辑，war文件可直接放入tomcat部署。

10.要使用SpringMVC+Mybatis+spring的整合，参见[http://git.oschina.net/shenzhanwang/SSM](http://git.oschina.net/shenzhanwang/SSM)  

效果图：
![输入图片说明](http://git.oschina.net/uploads/images/2016/1121/093409_8992d5b1_1110335.png "在这里输入图片标题")
![输入图片说明](http://git.oschina.net/uploads/images/2016/1121/093421_533bef25_1110335.png "在这里输入图片标题")

### 附录：个人作品索引目录（持续更新）

#### 基础篇:职业化，从做好OA系统开始
1. [SpringMVC,Mybatis,Spring三大框架的整合实现增删改查](https://gitee.com/shenzhanwang/SSM)![输入图片说明](https://img.shields.io/badge/-%E7%B2%BE%E5%93%81-orange.svg "在这里输入图片标题")
2. [Struts2,Hibernate,Spring三大框架的整合实现增删改查](https://gitee.com/shenzhanwang/S2SH)
3. [Spring,SpringMVC和Hibernate的整合实现增删改查](https://gitee.com/shenzhanwang/SSH)
4. [Spring平台整合activiti工作流引擎实现OA开发](https://gitee.com/shenzhanwang/Spring-activiti)![输入图片说明](https://img.shields.io/badge/-%E7%B2%BE%E5%93%81-orange.svg "在这里输入图片标题")
5. [Spring发布与调用REST风格的WebService](https://gitee.com/shenzhanwang/Spring-REST)
6. [Spring整合Apache Shiro框架，实现用户管理和权限控制](https://gitee.com/shenzhanwang/Spring-shiro)
7. [使用Spring security做权限控制](https://gitee.com/shenzhanwang/spring-security-demo)
8. [Spring整合Jasig CAS框架实现单点登录](https://gitee.com/shenzhanwang/Spring-cas-sso)
#### 中级篇：中间件的各种姿势
9. [Spring连接mongoDB数据库实现增删改查](https://gitee.com/shenzhanwang/Spring-mongoDB)
10. [Spring连接Redis实现缓存](https://gitee.com/shenzhanwang/Spring-redis)
11. [Spring连接图存数据库Neo4j实现增删改查](https://gitee.com/shenzhanwang/Spring-neo4j)
12. [Spring平台整合消息队列ActiveMQ实现发布订阅、生产者消费者模型（JMS）](https://gitee.com/shenzhanwang/Spring-activeMQ)
13. [Spring整合消息队列RabbitMQ实现四种消息模式（AMQP）](https://gitee.com/shenzhanwang/Spring-rabbitMQ)
14. Spring框架的session模块实现集中式session管理（[购买](https://www.fageka.com/store/item/s/id/fwW1QEK2848.html)）
15. [Spring整合websocket实现即时通讯](https://gitee.com/shenzhanwang/Spring-websocket)![输入图片说明](https://img.shields.io/badge/-%E7%B2%BE%E5%93%81-orange.svg "在这里输入图片标题")
16. 使用Spring boot整合mybatis,rabbitmq,redis,mongodb实现增删改查（[购买](https://www.fageka.com/store/item/s/id/0feQDHL1913.html)）
17. [Spring MVC整合FastDFS客户端实现文件上传](https://gitee.com/shenzhanwang/Spring-fastdfs)
18. 23种设计模式，源码、注释、使用场景（[购买](https://www.fageka.com/store/item/s/id/TuSSL2r3330.html)）
19. [使用ETL工具Kettle的实例](https://gitee.com/shenzhanwang/Kettle-demo)
20. Git指南和分支管理策略（[购买](https://www.fageka.com/store/item/s/id/Z7uh2iF1620.html)）
21. 使用数据仓库进行OLAP数据分析（Mysql+Kettle+Zeppelin）（[购买](https://www.fageka.com/store/item/s/id/malQqky4959.html)）![输入图片说明](https://img.shields.io/badge/-%E7%B2%BE%E5%93%81-orange.svg "在这里输入图片标题")
#### 高级篇：架构之美
22. [zookeeper原理、架构、使用场景和可视化](https://gitee.com/shenzhanwang/zookeeper-practice)
23. Spring boot整合Apache dubbo v2.7实现分布式服务治理（SOA架构）（[购买](https://www.fageka.com/store/item/s/id/tTEHOF42241.html)）![输入图片说明](https://img.shields.io/badge/-%E7%B2%BE%E5%93%81-orange.svg "在这里输入图片标题")
24. 使用Spring Cloud实现微服务架构（MSA架构）![输入图片说明](https://img.shields.io/badge/-%E7%B2%BE%E5%93%81-orange.svg "在这里输入图片标题")  
> -- vDalston.SR5（[购买](https://www.fageka.com/store/item/s/id/5T5cEY80304.html))  
-- vFinchley.SR2（[购买](https://www.fageka.com/store/item/s/id/5WkybHC1025.html)）
25. 使用jenkins+centos+git+maven搭建持续集成环境自动化部署分布式服务（[购买](https://www.fageka.com/store/item/s/id/TvLt0pr4205.html)）
26. 使用docker+compose+jenkins+gitlab+spring cloud实现微服务的编排、持续集成和动态扩容（[购买](https://www.fageka.com/store/item/s/id/7Gi4FeN2111.html)）
27. 使用FastDFS搭建分布式文件系统（高可用、负载均衡）（[购买](https://www.fageka.com/store/item/s/id/sAKgl2n4209.html)）
28. 搭建高可用nginx集群和Tomcat负载均衡（[购买](https://www.fageka.com/store/item/s/id/78bvd6N2534.html)）
29. 搭建可扩展的ActiveMQ高可用集群（[购买](https://www.fageka.com/store/item/s/id/H1nWZ4j4443.html)）
30. 实现Mysql数据库的主从复制、读写分离、分表分库、负载均衡和高可用（[购买](https://www.fageka.com/store/item/s/id/lojrGCH2016.html)）
31. 搭建高可用redis集群实现分布式缓存（[购买](https://www.fageka.com/store/item/s/id/02HwT2W4038.html)）
32. [Spring整合SolrJ实现全文检索](https://gitee.com/shenzhanwang/Spring-solr)
#### 特别篇：分布式事务和并发控制
33. 基于可靠消息最终一致性实现分布式事务（activeMQ）（[购买](https://www.fageka.com/store/item/s/id/qwCZgHD2224.html)）
34. 使用TCC框架实现分布式事务（dubbo版）（[购买](https://www.fageka.com/store/item/s/id/woVwDpD0145.html)）
35. 使用TCC框架实现分布式事务（Spring Cloud版）（[购买](https://www.fageka.com/store/item/s/id/VZ4lvg40739.html)）
36. 决战高并发：数据库锁机制和事务隔离级别的实现（[购买](https://www.fageka.com/store/item/s/id/Xvk7DZI2400.html)）![输入图片说明](https://img.shields.io/badge/-%E7%B2%BE%E5%93%81-orange.svg "在这里输入图片标题")
37. 决战高并发：使用redis实现分布式锁（[购买](https://www.fageka.com/store/item/s/id/uFQStQ61656.html)）![输入图片说明](https://img.shields.io/badge/-%E7%B2%BE%E5%93%81-orange.svg "在这里输入图片标题")
38. 决战高并发：使用zookeeper实现分布式锁（[购买](https://www.fageka.com/store/item/s/id/NQp8kpF1940.html)）
39. 决战高并发：Java多线程编程实例（[购买](https://www.fageka.com/store/item/s/id/k6MzK041644.html)）
40. 决战高并发：使用netty实现高性能NIO通信（[购买](https://www.fageka.com/store/item/s/id/VtwnbVN5319.html)）

### 网店入口
[我的网店](https://www.fageka.com/Store/Index/shop/id/1zxrETbHcz)
   
