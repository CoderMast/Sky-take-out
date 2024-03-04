## 开始之前

对你有用的话，希望能给项目点个Star，非常感谢。

对于项目的任何问题，或者你在本地部署时遇到的无法解决的问题，都可以提交issues，又可能你遇到的问题别人已经提交了issues，那么你就直接可以得到解决。没有解决的我会在第一时间进行解决和答复

欢迎关注我的微信公众号，可以随时和我交流。

![](https://github.com/CoderMast/codermast/blob/1efef0209335977754163ebc513b7d4b91eeaf41/images/%E6%89%AB%E7%A0%81_%E7%99%BD%E8%89%B2%E7%89%88.png)


## 项目介绍

本项目是参考B站黑马程序员的《苍穹外卖》系列教程，并加上本人的一些修改所编写的一个基于 SpringBoot + MySql + Mybatis-plus 的前后端分离的外卖管理系统。

本项目对原视频教程中的部分做出了修改，原教程使用的是 Mybatis，本项目使用 Mybatis-plus。

目前项目还在编写阶段，内容也会不断完善更新，有问题的小伙伴可以评论区交流，感谢支持。

## 项目演示

- 后台演示：
- 前台演示：
- 小程序演示：

## 项目部署

// TODO 部署教程待更新...


## 项目模块

- sky-take-out：maven 父工程，统一管理依赖版本，聚合其他子模块
- sky-common：子模块，存放公共类，例如：工具类、常量类
- sky-pojo：子模块，存放实体类，vo、DTO等
- sky-server：子模块，后端服务，存放配置文件、Controller、Service、Mapper等
- sky-front：存放项目的前端项目文件
- sky-sql：存放项目的数据库文件

- Entity：实体，通常和数据库中的表对应
- DTO：数据传输对象，通常使用
- VO：视图对象，为前端展示数据提供的对象。
- POJO：普通 Java 对象，只有属性和对应的 getter 和 setter