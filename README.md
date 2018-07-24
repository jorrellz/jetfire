## 前世今生

Jetfire《天火》介绍： 
变形模式：太空穿梭机。G1玩具为VF-1S。SR-71“黑鸟”侦察机 (真人电影版） 
性格：胆大心细，性格温和，秉持坚守和平的信念，重视友谊 
身世：在大战前塞伯坦的“黄金时代”，天火是一位科学家，致力于对于科学研究。
格言：“在众多科学奥妙中，有如何取得胜利的钥匙。”

## 平台简介

天火系统基于SpringBoot与shiro实现基于数据库的细粒度动态权限管理系统实例，
项目代码简洁,注释丰富,上手容易, 包含许多基础模块(用户管理,角色管理,部门管理,字典管理等10个模块),
可直接作为一个后台管理系统的脚手架。

## 技术选型

技术|说明|版本
---|:--:|---:
Spring Boot|核心框架|2.0.3
Apache Shiro|安全框架|1.4.0
Thymeleaf|模板引擎|2.0.0
MyBatis|持久层框架|3.4.6
Quartz|定时任务|2.3.0
Druid|数据库连接池|1.1.10
Swagger2|接口文档|2.7.0


## 内置功能

1.  用户管理：用户是系统操作者，该功能主要完成系统用户配置。
2.  部门管理：配置系统组织机构（公司、部门、小组），树结构展现。
3.  岗位管理：配置系统用户所属担任职务。
4.  菜单管理：配置系统菜单，操作权限，按钮权限标识等。
5.  角色管理：角色菜单权限分配、设置角色按机构进行数据范围权限划分。
6.  字典管理：对系统中经常使用的一些较为固定的数据进行维护。
7.  参数管理：对系统动态配置常用参数。
8.  通知公告：系统通知公告信息发布维护。
9.  操作日志：系统正常操作日志记录和查询；系统异常信息日志记录和查询。
10. 登录日志：系统登录日志记录查询包含登录异常。
11. 在线用户：当前系统中活跃用户状态监控。
12. 定时任务：在线（添加、修改、删除)任务调度包含执行结果日志。
13. 代码生成：前后端代码的生成（java、html、xml、sql)支持CRUD下载 。
14. 系统接口：根据业务代码自动生成相关的api接口文档。
15. 在线构建器：拖动表单元素生成相应的HTML代码。
16. 连接池监视：监视当期系统数据库连接池状态，可进行分析SQL找出系统性能瓶颈。
