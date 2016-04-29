
![Lessgo Favicon](img/favicon.png)
Lessgo 是一款Go 语言开发的简单、稳定、高效、灵活的 web开发框架。它的项目组织形式经过精心设计，实现前后端分离、系统与业务分离，完美兼容MVC与MVVC等多种开发模式，非常利于企业级应用与API接口的开发。当然，最值得关注的是它突破性地支持了运行时路由重建，开发者可在Admin后台轻松实现启用/禁用模块与操作，添加/移除中间件等功能！同时，它推荐以HandlerFunc与MiddlewareFunc为基础的函数式编程，也令开发变得更加灵活富有趣味性。 此外它也博采众长，核心架构基于echo v2并增强优化，数据库引擎内置为xorm，模板引擎内置为pongo2，其他某些功能模块改写自beego以及其他优秀开源项目。（在此感谢这些优秀的开源项目）

# 目录

- [综述](Introduction.md)
- [安装部署](Install.md)
- [开始Lessgo之旅](Develop01.md)
- [系统配置项]( )
  - [App.config](Develop02-1.md)
  - [DB.config](Develop02-2.md)
- [运行时路由](Develop03.md)
- [带描述Handle]( )
- [基于xorm的model开发]( )
- [中间件开发]( )
- [Session]( )
- [多数据库连接]( )
- [文件上传下载]( )
- [系统log]( )
- [Swagger]( )
- [模块开发实例]( )
   - [服务端开发]( )
   - [web客户端开发]( )
- [框架API]( )
- [扩展模块]( )
  - [Admin管理模块]( )
  - [SQLMAP引擎]( )
  - [帐号权限模块]( )
- [相关参考](.md)
    - [echo v2]()
    - [xorm]()

