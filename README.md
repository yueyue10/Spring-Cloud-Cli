SpringCloud 脚手架
===

简易教程
---
https://blog.csdn.net/u014271612/article/details/82866913

项目架构图
---
![image](https://github.com/xuyaohui/cloud-ida-cli/blob/master/images/%E6%9E%B6%E6%9E%84%E5%9B%BE.png)

所使用相关技术：
---

注册中心：Spring Cloud Eureka

网关中心：Spring Cloud Zuul

服务配置：Spring Cloud Config

链路追踪：Spring Cloud Zipkin

数据库连接：Druid、Mybatis

服务鉴权：Shiro+JWT

数据库：PostgreSQL

日志收集：ELK(服务安装在虚拟机)

服务之间调用： Feign

熔断机制：Hystrix

消息队列：RabbitMQ

系统各模块介绍
---

| Project       | Project介绍(点击查看详情)    |
| --------      |          :----:            |
| cloud-ida         |    项目父模块，所有以下子模块依赖该父模块（可在该pom文件加入所需要的依赖）  |
| cloud-ida-eureka       |    [服务发现、注册中心][1]   |
| cloud-ida-config       |    [分布式配置中心，可将各模块所需的配置放到该中心（dev/uat/pro）][2]   |
| cloud-ida-admin       |    [后台管理模块（包含前后端），包括用户、角色、权限管理及服务监控][3]   |
| cloud-ida-admin-server       |    [使用springboot admin，监控各服务运行状况][4]   |
| cloud-ida-common       |    [common模块，封装模块常用bean及工具类][5]   |
| cloud-ida-service       |    [业务服务模块（可按业务拆分成多个服务）][6]   |
| cloud-ida-zipkin      |    [服务链路追踪][7]   |
| cloud-ida-zuul      |    [微服务网关层，所有请求都经过网关请求，此模块中也有shiro认证、鉴权][8]   |

[1]: https://github.com/yueyue10/Spring-Cloud-Cli/tree/master/cloud-ida-eureka
[2]: https://github.com/yueyue10/Spring-Cloud-Cli/tree/master/cloud-ida-config
[3]: https://github.com/yueyue10/Spring-Cloud-Cli/tree/master/cloud-ida-admin  
[4]: https://github.com/yueyue10/Spring-Cloud-Cli/tree/master/cloud-ida-admin-server
[5]: https://github.com/yueyue10/Spring-Cloud-Cli/tree/master/cloud-ida-common
[6]: https://github.com/yueyue10/Spring-Cloud-Cli/tree/master/cloud-ida-service
[7]: https://github.com/yueyue10/Spring-Cloud-Cli/tree/master/cloud-ida-zipkin 
[8]: https://github.com/yueyue10/Spring-Cloud-Cli/tree/master/cloud-ida-zuul 





