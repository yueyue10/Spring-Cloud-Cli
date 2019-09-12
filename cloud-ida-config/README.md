# config配置

项目配置
---

* pom配置
    * 添加spring-cloud-config-server依赖
* Application配置
    * 添加@EnableConfigServer注解
* application.properties配置
    * 配置application.name
    * 配置server.port
    * 配置eureka服务地址
    * 添加配置文件路径：search-locations
    * 配置运行环境：profiles.active
* 增加配置文件
    * resources下面新建config文件夹
    * 创建cloud-ida-admin-dev.properties为cloud-ida-admin服务配置数据库连接
    ![ic_config.png](https://raw.githubusercontent.com/yueyue10/Spring-Cloud-Cli/master/images/ic_config.png)
