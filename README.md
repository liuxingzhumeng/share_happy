# 快乐分享论坛

该论坛项目源码主要分为3个模块进行上传

1. >>>【当前】SpringBoot服务器源码<<<
2. Vue单页面后台管理源码
3. LayUI主页源

当前项目为论坛系统的后台服务项目，主要给2 和3 点提供json类型的数据接口，前后端分离开发需要注意的是，浏览器的同源策略，防止接口异常连接不上。

## 1. 关键技术 

- 项目中主要是在Maven项目的基础上搭建起来的
- 项目整体为Spring Boot项目
- 在Spring Boot项目中会提供非常多的接口，而写接口文档也是毕竟费时的事情这里用swagger 根据接口自动生成接口文档
- 内置通过spring-boot-starter-mail进行邮箱的发送
- 还有一个spring-security-core 对用户密码进行加密的
- 常用的分页插件pagehelper
- 对于文章类系统，有个全文搜索技术elasticsearch很重要
- 最后就是一个钉钉登录功能的插件了
