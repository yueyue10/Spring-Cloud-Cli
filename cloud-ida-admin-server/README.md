# admin-server配置

参考：

https://blog.csdn.net/forezp/article/details/86105850
https://www.jianshu.com/p/25d5a85ce8dd

项目配置
---

* pom配置：
    * 添加spring-boot-admin-server依赖
    * 添加spring-boot-admin-server-ui依赖
* Application配置：
    * 添加@EnableAdminServer注解
* application.properties配置
    * 配置eureka
    * 配置server.port
    * 配置application.name
* **自定义admin server界面**
    * 在resources目录下新建spring-boot-admin-server-ui文件夹
    * 复制admin的资源文件到上面的文件夹下
    * 修改index.html文件
* 运行项目即可看到注册的服务和eureka功能类似，不启动对于整个项目也没什么影响。
    * 这里有个问题：(~~Spring Boot Admin后台没有wallboard~~)
