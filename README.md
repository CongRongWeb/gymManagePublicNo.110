<p><h1 align="center">基于Java+Springboot+Vue的健身房管理系统</h1></p>

- <b>完整代码获取地址：从戎源码网 ([https://armycodes.com/](https://armycodes.com/))</b>
- <b>技术探讨、资料分享，请加QQ群：692619798</b> 
- <b>作者微信：19941326836  QQ：952045282</b> 
- <b>承接计算机毕业设计、Java毕业设计、Python毕业设计、深度学习、机器学习</b>
- <b>选题+开题报告+任务书+程序定制+安装调试+论文+答辩ppt 一条龙服务</b>
- <b>所有选题地址 ([https://github.com/YuLin-Coder/AllProjectCatalog](https://github.com/YuLin-Coder/AllProjectCatalog)) </b>

## 一、系统介绍
本项目前后端分离(还有ssm版本)，分为管理员、教练、用户三种角色

### 1、用户：
- 注册登录、购买课程、商品购买、购物车、商家浏览、轮播图、公告信息、余额充值、会员办卡管理、到期提醒、会员续卡、报名课程、订单管理、个人信息、修改密码
### 2、教练：
- 课程管理、报名管理、注册登录
### 3、管理员：
- 会员管理、教练管理、充值管理、会员类型管理、会员办卡管理、会员续卡管理、课程管理、报名课程管理、商品管理、订单管理、公告信息管理、轮播图管理
## 二、所用技术

后端技术栈：

- Springboot
- MybatisPlus
- Mysql
- Maven

前端技术栈：

- Vue 
- Vue-router 
- axios 
- element-ui

## 三、环境介绍

基础环境:IDEA/eclipse, JDK1.8, Mysql5.7及以上, Maven3.6, node14, navicat

所有项目以及源代码本人均调试运行无问题 可支持远程调试运行

## 四、页面截图
文档截图
![contents](./picture/picture0.png)
### 1、用户
![contents](./picture/picture1.png)
![contents](./picture/picture2.png)
![contents](./picture/picture3.png)
![contents](./picture/picture4.png)
![contents](./picture/picture5.png)
![contents](./picture/picture6.png)
![contents](./picture/picture7.png)
![contents](./picture/picture8.png)
![contents](./picture/picture9.png)
![contents](./picture/picture10.png)
![contents](./picture/picture11.png)
![contents](./picture/picture12.png)
![contents](./picture/picture13.png)
![contents](./picture/picture14.png)
![contents](./picture/picture15.png)
![contents](./picture/picture16.png)
![contents](./picture/picture17.png)
![contents](./picture/picture18.png)
![contents](./picture/picture19.png)
![contents](./picture/picture20.png)
![contents](./picture/picture21.png)
### 2、教练：
![contents](./picture/picture22.png)
![contents](./picture/picture23.png)
![contents](./picture/picture24.png)
![contents](./picture/picture25.png)
### 3、管理员：
![contents](./picture/picture26.png)
![contents](./picture/picture27.png)
![contents](./picture/picture28.png)
![contents](./picture/picture29.png)
![contents](./picture/picture30.png)
![contents](./picture/picture31.png)
![contents](./picture/picture32.png)
![contents](./picture/picture33.png)
![contents](./picture/picture34.png)
![contents](./picture/picture35.png)
![contents](./picture/picture36.png)
![contents](./picture/picture37.png)
![contents](./picture/picture38.png)
## 五、浏览地址
前台登录页面: http://localhost:8081

- 用户账号/密码：用户1/123456

后台登录页面: http://localhost:8082

- 教练账号/密码：教练账号1/123456
- 管理员账号/密码：admin/admin
## 六、部署教程

1. 使用Navicat或者其它工具，在mysql中创建对应名称的数据库，并执行项目的sql

2. 使用IDEA/Eclipse导入gym项目，导入时，若为maven项目请选择maven; 等待依赖下载完成

3. 修改resources目录下面application.yml里面的数据库配置

4. src/main/java/com/SpringbootSchemaApplication.java启动后端

5. vscode或idea打开src/main/resources/front/front项目

6. 在编译器中打开terminal，执行npm install 依赖下载完成后执行 npm run serve,执行成功后会显示前台管理访问地址

7. vscode或idea打开src/main/resources/admin/admin项目

8. 在编译器中打开terminal，执行npm install 依赖下载完成后执行 npm run serve,执行成功后会显示后台管理访问地址

