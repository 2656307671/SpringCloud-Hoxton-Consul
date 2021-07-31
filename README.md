### Consul是什么？

Consul 是一套开源的分布式服务发现和配置管理系统，由 HashiCorp 公司用 Go 语言开发。
 
提供了微服务系统中的服务治理、配置中心、控制总线等功能。这些功能中的每一个都可以根据需要单独使用，也可以一起使用以构建全方位的服务网格，总之Consul提供了一种完整的服务网格解决方案。
 
它具有很多优点。包括： 基于 raft 协议，比较简洁； 支持健康检查, 同时支持 HTTP 和 DNS 协议 支持跨数据中心的 WAN 集群 提供图形界面 跨平台，支持 Linux、Mac、Windows

### Consul能干嘛？

1.服务发现：提供HTTP和DNS两种发现方式

2.健康监测：支持多种方式，HTTP、TCP、Docker、Shell脚本定制化监控

3.KV存储：key-value的存储方式

4.多数据中心：Consul支持多数据中心

5.可视化Web界面
