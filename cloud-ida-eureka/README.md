# eureka配置
参考：
https://blog.csdn.net/feng641307267/article/details/80682838
https://blog.csdn.net/qq_33616529/article/details/78291101

项目配置
---

* pom配置eureka依赖
* Application配置eureka
* application.properties配置eureka
* **自定义eureka server界面**
    * 将spring-cloud-netflix-eureka-server源码的界面文件拷贝到项目的相同目录下[参考文档][1]
    * 修改navbar.ftl文件，将英文字段改成中文字段
    ![ic_ribbon.png](https://github.com/yueyue10/Spring-Cloud-Cli/blob/master/cloud-ida-eureka/doc/ic_navbar.png?raw=true)
    * 修改status.ftl文件，将英文字段改成中文字段
    
[1]:https://blog.csdn.net/feng641307267/article/details/80682838