# 后端面试专题：系列目录

按技术分类阅读，或从业务场景与线上问题反向定位相关机制。各篇保留独立的问题目录、题设、正文解答和递进追问。

| 专题 | 阅读范围 | 主问题 |
|---|---|---:|
| [一、Java](01-java.md) | 基础、集合、并发、I/O 与 JVM | 133 |
| [二、Golang](02-golang.md) | 数据结构、并发、调度与内存管理 | 76 |
| [三、Spring 系列](03-spring.md) | 容器、代理、事务与 Web 开发 | 60 |
| [四、MySQL](04-mysql.md) | 表设计、索引、事务与查询优化 | 94 |
| [五、Redis](05-redis.md) | 数据结构、持久化、集群与缓存设计 | 78 |
| [六、消息队列](06-message-queues.md) | 可靠投递、消费语义与三类 MQ | 42 |
| [七、ZooKeeper](07-zookeeper.md) | 节点、会话、ZAB 与分布式协调 | 15 |
| [八、Elasticsearch](08-elasticsearch.md) | 索引建模、读写流程与查询优化 | 22 |
| [九、etcd](09-etcd.md) | Raft、一致性、Watch 与 Lease | 12 |
| [十、计算机网络](10-networks.md) | TCP、HTTP、TLS 与请求全链路 | 39 |
| [十一、操作系统](11-operating-systems.md) | 进程、内存、同步与 I/O | 27 |
| [十二、Linux](12-linux.md) | 命令、日志、网络与资源诊断 | 23 |
| [十三、场景题](13-system-design.md) | 高并发、订单支付与业务一致性 | 35 |
| [十四、分布式](14-distributed-systems.md) | 一致性、锁、事务、ID 与任务调度 | 30 |
| [十五、微服务](15-microservices.md) | 服务通信、治理、安全与发布 | 41 |
| [十六、线上问题排查](16-troubleshooting.md) | CPU、内存、数据库与中间件 | 40 |
| [十七、智力题](17-puzzles.md) | 称量、概率、博弈与信息推理 | 14 |

## 技术小节索引

### 一、Java

- [1. Java 基础](01-java.md#1-java-基础)
- [2. Java 集合框架](01-java.md#2-java-集合框架)
- [3. Java 并发](01-java.md#3-java-并发)
- [4. Java I/O](01-java.md#4-java-io)
- [5. Java 虚拟机](01-java.md#5-java-虚拟机)

### 二、Golang

- [1. Go 基础](02-golang.md#1-go-基础)
- [2. Go 数据结构](02-golang.md#2-go-数据结构)
- [3. Go 接口与反射](02-golang.md#3-go-接口与反射)
- [4. Go 并发编程](02-golang.md#4-go-并发编程)
- [5. Go 调度机制](02-golang.md#5-go-调度机制)
- [6. Go 内存管理](02-golang.md#6-go-内存管理)
- [7. Go 垃圾回收](02-golang.md#7-go-垃圾回收)
- [8. Go 工程实践](02-golang.md#8-go-工程实践)

### 三、Spring 系列

- [1. Spring 基础](03-spring.md#1-spring-基础)
- [2. Spring IoC 与 Bean 管理](03-spring.md#2-spring-ioc-与-bean-管理)
- [3. Spring AOP](03-spring.md#3-spring-aop)
- [4. Spring 事务](03-spring.md#4-spring-事务)
- [5. Spring MVC](03-spring.md#5-spring-mvc)
- [6. Spring Boot](03-spring.md#6-spring-boot)
- [7. MyBatis](03-spring.md#7-mybatis)

### 四、MySQL

- [1. MySQL 基础](04-mysql.md#1-mysql-基础)
- [2. MySQL 存储引擎](04-mysql.md#2-mysql-存储引擎)
- [3. MySQL 索引](04-mysql.md#3-mysql-索引)
- [4. MySQL 事务与 MVCC](04-mysql.md#4-mysql-事务与-mvcc)
- [5. MySQL 锁机制](04-mysql.md#5-mysql-锁机制)
- [6. MySQL 日志](04-mysql.md#6-mysql-日志)
- [7. SQL 编写与优化](04-mysql.md#7-sql-编写与优化)
- [8. 主从复制与读写分离](04-mysql.md#8-主从复制与读写分离)
- [9. 分库分表](04-mysql.md#9-分库分表)

### 五、Redis

- [1. Redis 基础](05-redis.md#1-redis-基础)
- [2. Redis 数据结构](05-redis.md#2-redis-数据结构)
- [3. Redis 线程模型与命令执行](05-redis.md#3-redis-线程模型与命令执行)
- [4. Redis 持久化](05-redis.md#4-redis-持久化)
- [5. 过期删除与内存淘汰](05-redis.md#5-过期删除与内存淘汰)
- [6. 主从复制与集群](05-redis.md#6-主从复制与集群)
- [7. 缓存穿透、击穿与雪崩](05-redis.md#7-缓存穿透击穿与雪崩)
- [8. 缓存一致性](05-redis.md#8-缓存一致性)
- [9. Redis 分布式锁](05-redis.md#9-redis-分布式锁)

### 六、消息队列

- [1. 消息队列基础](06-message-queues.md#1-消息队列基础)
- [2. 消息可靠性](06-message-queues.md#2-消息可靠性)
- [3. 消息消费机制](06-message-queues.md#3-消息消费机制)
- [4. Kafka](06-message-queues.md#4-kafka)
- [5. RocketMQ](06-message-queues.md#5-rocketmq)
- [6. RabbitMQ](06-message-queues.md#6-rabbitmq)

### 七、ZooKeeper

- [1. ZooKeeper 基础](07-zookeeper.md#1-zookeeper-基础)
- [2. 数据模型与节点](07-zookeeper.md#2-数据模型与节点)
- [3. Watcher 与会话机制](07-zookeeper.md#3-watcher-与会话机制)
- [4. ZAB 协议](07-zookeeper.md#4-zab-协议)
- [5. Leader 选举](07-zookeeper.md#5-leader-选举)
- [6. 分布式协调](07-zookeeper.md#6-分布式协调)

### 八、Elasticsearch

- [1. Elasticsearch 基础](08-elasticsearch.md#1-elasticsearch-基础)
- [2. 索引与分词](08-elasticsearch.md#2-索引与分词)
- [3. 数据读写机制](08-elasticsearch.md#3-数据读写机制)
- [4. 分片与副本](08-elasticsearch.md#4-分片与副本)
- [5. 查询优化](08-elasticsearch.md#5-查询优化)
- [6. 数据同步](08-elasticsearch.md#6-数据同步)

### 九、etcd

- [1. etcd 基础](09-etcd.md#1-etcd-基础)
- [2. Raft 协议](09-etcd.md#2-raft-协议)
- [3. 一致性与高可用](09-etcd.md#3-一致性与高可用)
- [4. 分布式协调](09-etcd.md#4-分布式协调)

### 十、计算机网络

- [1. 网络基础](10-networks.md#1-网络基础)
- [2. TCP 与 UDP](10-networks.md#2-tcp-与-udp)
- [3. HTTP](10-networks.md#3-http)
- [4. HTTPS 与 TLS](10-networks.md#4-https-与-tls)
- [5. DNS](10-networks.md#5-dns)
- [6. WebSocket 与长连接](10-networks.md#6-websocket-与长连接)
- [7. 网络安全](10-networks.md#7-网络安全)

### 十一、操作系统

- [1. 进程与线程](11-operating-systems.md#1-进程与线程)
- [2. 进程调度](11-operating-systems.md#2-进程调度)
- [3. 进程通信](11-operating-systems.md#3-进程通信)
- [4. 同步与死锁](11-operating-systems.md#4-同步与死锁)
- [5. 内存管理](11-operating-systems.md#5-内存管理)
- [6. 系统调用](11-operating-systems.md#6-系统调用)
- [7. I/O 模型与多路复用](11-operating-systems.md#7-io-模型与多路复用)

### 十二、Linux

- [1. Linux 基础](12-linux.md#1-linux-基础)
- [2. 文件与权限](12-linux.md#2-文件与权限)
- [3. 进程管理](12-linux.md#3-进程管理)
- [4. Shell 与文本处理](12-linux.md#4-shell-与文本处理)
- [5. 日志分析](12-linux.md#5-日志分析)
- [6. 网络工具](12-linux.md#6-网络工具)
- [7. 资源监控](12-linux.md#7-资源监控)

### 十三、场景题

- [1. 高并发系统设计](13-system-design.md#1-高并发系统设计)
- [2. 秒杀与库存设计](13-system-design.md#2-秒杀与库存设计)
- [3. 订单与支付设计](13-system-design.md#3-订单与支付设计)
- [4. 登录与鉴权设计](13-system-design.md#4-登录与鉴权设计)
- [5. 短链接系统设计](13-system-design.md#5-短链接系统设计)
- [6. 聊天与消息推送](13-system-design.md#6-聊天与消息推送)
- [7. 计数与排行榜设计](13-system-design.md#7-计数与排行榜设计)
- [8. 文件上传设计](13-system-design.md#8-文件上传设计)
- [9. 数据迁移与扩容](13-system-design.md#9-数据迁移与扩容)

### 十四、分布式

- [1. 分布式基础](14-distributed-systems.md#1-分布式基础)
- [2. 一致性理论与协议](14-distributed-systems.md#2-一致性理论与协议)
- [3. 分布式锁](14-distributed-systems.md#3-分布式锁)
- [4. 分布式事务](14-distributed-systems.md#4-分布式事务)
- [5. 分布式 ID](14-distributed-systems.md#5-分布式-id)
- [6. 一致性哈希](14-distributed-systems.md#6-一致性哈希)
- [7. 幂等与重试](14-distributed-systems.md#7-幂等与重试)
- [8. 分布式任务调度](14-distributed-systems.md#8-分布式任务调度)

### 十五、微服务

- [1. 微服务基础](15-microservices.md#1-微服务基础)
- [2. RPC 与服务通信](15-microservices.md#2-rpc-与服务通信)
- [3. 服务注册与发现](15-microservices.md#3-服务注册与发现)
- [4. 配置中心](15-microservices.md#4-配置中心)
- [5. 网关与负载均衡](15-microservices.md#5-网关与负载均衡)
- [6. 限流、熔断与降级](15-microservices.md#6-限流熔断与降级)
- [7. 认证与授权](15-microservices.md#7-认证与授权)
- [8. 链路追踪](15-microservices.md#8-链路追踪)
- [9. 服务发布](15-microservices.md#9-服务发布)

### 十六、线上问题排查

- [1. CPU 与负载排查](16-troubleshooting.md#1-cpu-与负载排查)
- [2. 内存与 GC 排查](16-troubleshooting.md#2-内存与-gc-排查)
- [3. 线程与协程排查](16-troubleshooting.md#3-线程与协程排查)
- [4. 接口与网络排查](16-troubleshooting.md#4-接口与网络排查)
- [5. MySQL 问题排查](16-troubleshooting.md#5-mysql-问题排查)
- [6. Redis 问题排查](16-troubleshooting.md#6-redis-问题排查)
- [7. 消息队列问题排查](16-troubleshooting.md#7-消息队列问题排查)
- [8. 排查工具与性能分析](16-troubleshooting.md#8-排查工具与性能分析)

### 十七、智力题

- [1. 称量与比较](17-puzzles.md#1-称量与比较)
- [2. 概率与随机](17-puzzles.md#2-概率与随机)
- [3. 逻辑与博弈](17-puzzles.md#3-逻辑与博弈)
- [4. 计数与信息推理](17-puzzles.md#4-计数与信息推理)
