# admin配置

参考：

https://www.e-learn.cn/thymeleaf/thymeleaf3-servlet3-helloworld
https://blog.csdn.net/kydkong/article/details/77507798
https://blog.csdn.net/LL142857/article/details/89242816

项目配置
---

* pom配置
    * 添加spring-boot-starter-thymeleaf依赖
    * 添加mysql-connector-java依赖
    * 添加spring-cloud-starter-config依赖
    * 添加net.sourceforge.nekohtml依赖(~~作用不清楚~~)
* application.properties配置
    * eureka配置
    * logging配置
    * mybatis配置
    * thymeleaf配置
    * config配置
* 代码编写：
    * dao层代码编写——底层，对数据库进行数据持久化操作。
    * service层代码编写——业务层，封装Dao层的操作，是使用一个或多个模型执行操作的方法。
    * controller层代码编写——业务控制层，负责接收数据和请求，调用Service层实现这个业务逻辑。
        * 主要包含：PermissionController、RoleController、UserController
            * 分别处理权限、角色、用户相关逻辑
        * 添加CoreController使用@Controller注解
            * 处理后台页面逻辑
    * 在resources下代码编写
        * mybatis的mapper.xml文件编写
        * 在templates目录下编写后台界面
* 项目结构图
    * ![image](https://github.com/yueyue10/Spring-Cloud-Cli/blob/master/images/ic_admin_process.png?raw=true)

