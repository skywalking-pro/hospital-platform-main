# Java-医院管理系统-毕业设计 

------------

![登陆界面](https://skywalking.pro/download/images/hospital-platform/WX20230217-144750@2x.png "登陆界面.png")

####  **功能设计图** 
![功能设计图](https://skywalking.pro/download/images/hospital-platform/WechatIMG802.jpeg "功能设计图.png")

####  **联系作者** 

![联系作者](https://skywalking.pro/download/platform/main-platform.png "联系作者.png")

**这是作者的微信二维码，如需本项目源代码，可扫码或者VX:SkywalkingPro联系作者。**  

![微信二维码-1](https://singer-coder-public.oss-cn-chengdu.aliyuncs.com/%E5%BE%AE%E4%BF%A1%E4%BA%8C%E7%BB%B4%E7%A0%81-1.png?x-oss-process=image/resize,p_50 "微信二维码-1.png")

**系统功能持续更新中。。。**
#### 介绍
 **这是一个基于SpringBoot2.X VUE2.6 Antd1.7.2  MyBatisPlus Shiro1.5.0 Java1.8 实现的具备系统管理、权限管理、患者管理、科室推荐、病历管理、病房管理、床位分配、床位管理、科室管理、护士管理、缴费管理、护士打卡签到、护士请假销假、留言信息、出院管理、转科管理等多个功能的医院管理系统， 可作为商用、毕业设计项目、快速开发模版项目。作者联系方式（WX:17001380020）见文末。** 
#### 项目所用技术
|技术点   | 描述  | 备注   |
| :------------: | :------------: | :------------: |
|  SpringBoot2.X | 先进的Spring集成框架  | 集成了最新版  |
| VUE2.6  |  前端交互框架 |   |
| Antd1.7.2 |  阿里出品的前端UI框架 |   |
| ANTD |  阿里出品的图表框架  | 好用且好看  |
| MyBatisPlus | 基于MyBatis封装的ORM框架  |方便查询   |
| Shiro1.5.0 | 经典而好用的权限框架  |  |
| Java1.8 | 最常用的Java版本  |使用了Java8新特性  |
| RBAC权限模型|纯动态的菜单权限设计，可控制权限到按钮级别  |纯动态的菜单权限设计  |
#### 清晰的注释
**项目的每个类和方法，都具备清晰的注释，适合阅读，注释如下图：**

**1. 类注释**

![类注释](https://www.skywalking.pro/download/images/meta/WX20230206-092916@2x.png "类注释")

**2. 数据库字段注释注释**

![类注释](https://www.skywalking.pro/download/images/meta/WX20230206-093511@2x.png "类注释")
#### 项目特有优势
1. 清晰的注释，每个方法，类，字段，都具备中文注释。
2. 部署方便，作者编写了一键启动的脚本，可以让Java后端完美运行在主流服务器上。
3. 代码符合行业规范，变量，类，命名简洁优雅。
4. 应用多种市面上的先进技术，方便学习和开发。
5. 具备完整的项目文档和技术文档，方便二次开发。
6. 具备前后端代码生成器，一键生成VUE以及Java后端代码。 
#### 它适合做什么？
1. 适合作为高校毕业设计。
2. 适合作为初学者学习使用。
3. 如果场景适合，可以作为商业使用。


#### 系统演示地址:
```
登录地址: https://www.skywalking.pro/hospital-platform
登录账号: admin
登录密码: 123456
```
**若演示地址不可用，可翻到文末扫码联系作者微信或者留言**

### 软件架构说明
该项目采用市面上比较流程的前后端分离架构，以SpringBoot技术栈为后端，以VUE为前端，采用优雅简洁漂亮的UI框架。系统采用前端发起请求，后端处理业务的方式进行交互，相对于传统的JSP，freemarker等技术有较大区别以及先进性。同时在权限控制方面有独到的创新，实现了VUE自定义指令，以控制系统权限到每一个系统按钮。是非常适合作为毕业设计以及学习的系统。
#### 前端技术
1. ElementUI
2. 页面,按钮级别权限控制。
3. 多个组件封装，调用方便。
4. Antv图表组件。
5. WebPack
6. ES6
7. 多环境打包。
8. VUE路由，过滤器，自定义指令。
9. 代码简洁，符合编码规范。
#### 后端技术
1. SpringBoot2.x
2. Shiro权限框架
3. Redis6.X最新版
4. MyBatis注解版
5. MySQL6.7
6. 分模块开发，自定义启动脚本，JVM调优
7. 多环境,前后端完全分离。
8. 代码生成器。
9. orika传输对象映射器。

### 系统技术文档
**为了让读者更好地理解系统技术原理，功能实现方法，故特地准备了系统技术文档，里面包含系统所使用的主要技术框架，运行说明，系统表设计，模块设计等。**
#### 系统技术文档截图

![系统技术文档截图](https://skywalking.pro/download/images/hospital-platform/WX20230217-145355@2x.png "系统技术文档截图.png")

### 项目代码展示

#### 前端VUE代码截图展示

![前端VUE代码截图展示](https://skywalking.pro/download/images/hospital-platform/WX20230217-145606@2x.png "前端VUE代码截图展示.png")

#### 后端Java代码截图展示

![后端Java代码截图展示](https://skywalking.pro/download/images/hospital-platform/WX20230217-145511@2x.png "后端Java代码截图展示.png")

#### 数据库表结构展示

![数据库表结构展示](https://skywalking.pro/download/images/hospital-platform/WX20230217-145648@2x.png "数据库表结构展示.png")

### 系统截图展示
#### 系统登陆
- 登陆界面

![登陆界面](https://skywalking.pro/download/images/hospital-platform/WX20230217-144750@2x.png "登陆界面.png")

#### 系统管理模块

- 系统主页

![系统主页](https://skywalking.pro/download/images/hospital-platform/WX20230217-145827@2x.png "系统主页.png")

![图表统计](https://skywalking.pro/download/images/hospital-platform/WX20230217-145857@2x.png "图表统计.png")

- 菜单管理

![菜单管理](https://skywalking.pro/download/images/hospital-platform/WX20230217-145931@2x.png "菜单管理.png")

![菜单编辑](https://skywalking.pro/download/images/hospital-platform/WX20230217-150016@2x.png "菜单编辑.png")

- 角色管理

![角色管理](https://skywalking.pro/download/images/hospital-platform/WX20230217-150054@2x.png "角色管理.png")

![角色编辑](https://skywalking.pro/download/images/hospital-platform/WX20230217-150140@2x.png "角色编辑.png")

- 系统用户管理

![系统用户](https://skywalking.pro/download/images/hospital-platform/WX20230217-150218@2x.png "系统用户.png")

![系统用户](https://skywalking.pro/download/images/hospital-platform/WX20230217-150248@2x.png
 "系统用户编辑.png")

#### 系统监控模块

- 系统日志

![系统日志](https://skywalking.pro/download/images/hospital-platform/WX20230217-152239@2x.png "系统日志.png")

#### 业务模块

- 患者管理

![患者管理](https://skywalking.pro/download/images/hospital-platform/WX20230217-152402@2x.png
 "患者管理")
 
![患者新增](https://skywalking.pro/download/images/hospital-platform/WX20230217-152437@2x.png
 "患者新增")
 
- 病历列表

![病历列表](https://skywalking.pro/download/images/hospital-platform/WX20230217-152613@2x.png
 "病历列表")
 
![病历编辑](https://skywalking.pro/download/images/hospital-platform/WX20230217-152702@2x.png
 "病历编辑")

- 科室管理

![科室管理](https://skywalking.pro/download/images/hospital-platform/WX20230217-152812@2x.png
 "科室管理")

![科室编辑](https://skywalking.pro/download/images/hospital-platform/WX20230217-152849@2x.png
 "科室编辑")

- 护士管理

![护工管理](https://skywalking.pro/download/images/hospital-platform/WX20230217-153731@2x.png "护工管理.png")

![护工编辑](https://skywalking.pro/download/images/hospital-platform/WX20230217-153833@2x.png "护工编辑.png")

- 护士签到

![护士管理](https://skywalking.pro/download/images/hospital-platform/WX20230217-153948@2x.png "护士管理.png")

![新增签到](https://skywalking.pro/download/images/hospital-platform/WX20230217-154047@2x.png "新增签到.png")

- 护士假勤

![护士假勤](https://skywalking.pro/download/images/hospital-platform/WX20230217-154255@2x.png "护士假勤.png")

![提交请假](https://skywalking.pro/download/images/hospital-platform/WX20230217-154400@2x.png "提交请假.png")

- 护士科室信息

![护士科室信息](https://skywalking.pro/download/images/hospital-platform/WX20230217-154719@2x.png "护士科室信息.png")

![编辑护士科室信息](https://skywalking.pro/download/images/hospital-platform/WX20230217-154831@2x.png "编辑护士科室信息.png")

- 转科记录

![转科记录](https://skywalking.pro/download/images/hospital-platform/WX20230217-154915@2x.png "转科记录.png")

![编辑转科记录](https://skywalking.pro/download/images/hospital-platform/WX20230217-155010@2x.png "编辑转科记录.png")

- 出院记录

![出院记录](https://skywalking.pro/download/images/hospital-platform/WX20230217-155050@2x.png "出院记录.png")

![编辑出院记录](https://skywalking.pro/download/images/hospital-platform/WX20230217-155158@2x.png "编辑出院记录.png")

- 病房管理

![病房管理](https://skywalking.pro/download/images/hospital-platform/WX20230217-155252@2x.png "病房管理.png")

![病房编辑](https://skywalking.pro/download/images/hospital-platform/WX20230217-155336@2x.png "病房编辑.png")

- 床位管理

![床位列表](https://skywalking.pro/download/images/hospital-platform/WX20230217-155433@2x.png "床位列表.png")

- 床位分配

![床位分配](https://skywalking.pro/download/images/hospital-platform/WX20230217-155533@2x.png "床位分配.png")

- 缴费管理

![缴费管理](https://skywalking.pro/download/images/hospital-platform/WX20230217-155618@2x.png "缴费管理.png")

![新增缴费](https://skywalking.pro/download/images/hospital-platform/WX20230217-155720@2x.png "新增缴费.png")

- 留言信息

![留言信息](https://skywalking.pro/download/images/hospital-platform/WX20230217-160129@2x.png "留言信息.png")

![新增留言](https://skywalking.pro/download/images/hospital-platform/WX20230217-160129@2x.png "新增留言.png")

#### 系统功能模块概要
+ 系统登陆
+ 系统主页
  - 系统统计图表
    * 系统访问量统计
    + 系统模块导航
+ 系统管理
  - 系统用户管理
    * 系统用户条件查询
    + 系统用户修改
    - 系统用户删除
	- 系统用户新增
  - 系统菜单管理
    * 系统菜单条件查询
    + 系统菜单修改(可级联修改)
    - 系统菜单删除
	- 系统菜单新增
  - 系统角色管理
    * 系统角色条件查询
    + 系统角色修改
    - 系统角色删除
	- 系统角色新增
  - 系统字典管理
    * 系统字典条件查询
    + 系统字典修改
    - 系统字典删除
	- 系统字典新增
+ 系统监控
  - 系统日志管理
    * 系统日志条件查询
    + 系统日志分析
	+ 系统访问IP分析
+ 患者管理
  - 患者管理
    * 患者管理条件查询
    + 患者管理新增
	* 患者管理修改
    + 患者管理批量删除
	+ 患者管理单个删除
	+ 智能科室推荐（用于根据患者的病状推荐用户去往什么科室，采用标签对比的算法
+ 病历管理
  - 病历管理
    * 病历管理条件查询
    + 病历管理新增
	* 病历管理修改
    + 病历管理批量删除
	+ 病历管理单个删除
+ 病房管理
  - 病房管理
    * 病房管理条件查询
    + 病房管理新增
	* 病房管理修改
    + 病房管理批量删除
	+ 病房管理单个删除
  - 床位列表
    * 床位条件查询
    + 床位新增
	* 床位修改
    + 床位批量删除
	+ 床位单个删除
  - 床位分配
    * 床位分配条件查询
    + 床位分配新增
	* 床位分配修改
    + 床位分配批量删除
	+ 床位分配单个删除
  + 床位信息
    - 床位信息管理
    * 床位信息条件查询
    + 床位信息新增
	* 床位信息修改
    + 床位信息批量删除
	+ 床位信息单个删除
+ 出院管理
  - 出院信息列表
    * 出院信息条件查询
    + 出院信息新增
	* 出院信息修改
    + 出院信息批量删除
	+ 出院信息单个删除
+ 转科管理
  - 转科信息列表
    * 转科信息条件查询
    + 转科信息新增
	* 转科信息修改
    + 转科信息批量删除
	+ 转科信息单个删除
+ 科室信息
  - 科室信息管理
    * 科室信息条件查询
    + 科室信息新增
	* 科室信息修改
    + 科室信息批量删除
	+ 科室信息单个删除
  - 护士管理
    * 护士信息条件查询
    + 护士信息新增
	* 护士信息修改
    + 护士信息批量删除
	+ 护士信息单个删除
	+ 护士请假销假
	+ 护士签到打卡
+ 缴费管理
  - 缴费列表
    * 缴费信息条件查询
    + 缴费信息新增
	* 缴费信息修改
    + 缴费信息批量删除
	+ 缴费信息单个删除
+ 探访申请信息
  - 探访申请信息管理
    * 探访申请信息条件查询
    + 探访申请信息新增
	* 探访申请信息修改
    + 探访申请信息批量删除
	+ 探访申请信息单个删除
+ 维修信息
  - 维修信息管理
    * 维修信息条件查询
    + 维修信息新增
	* 维修信息修改
    + 维修信息批量删除
	+ 维修信息单个删除
+ 活动信息
  - 活动管理
    * 活动条件查询
    + 活动新增
	* 活动修改
    + 活动批量删除
	+ 活动单个删除
+ 护工薪资信息
  - 护工薪资管理
    * 护工薪资条件查询
    + 护工薪资新增
	* 护工薪资修改
    + 护工薪资批量删除
	+ 护工薪资单个删除
+ 护工假勤信息
  - 护工假勤管理
    * 护工假勤信息条件查询
    + 护工假勤信息新增（提交）
	* 护工假勤信息修改
    + 护工假勤信息批量删除
	+ 护工假勤信息单个删除
+ 留言功能
  - 留言
    * 留言条件查询
	+ 留言新增（提交留言）
	* 留言修改
    + 留言批量删除
	+ 留言单个删除


#### 演示地址
```
登录地址: https://www.skywalking.pro/hospital-platform
登录账号: admin
登录密码: 123456
```
若演示地址不可用，可扫码联系作者微信或者留言

####  **联系作者** 

![联系作者](https://skywalking.pro/download/platform/main-platform.png "联系作者.png")

**这是作者的微信二维码，如需本项目源代码，可扫码或者VX:SkywalkingPro联系作者。**  

![微信二维码-1](https://singer-coder-public.oss-cn-chengdu.aliyuncs.com/%E5%BE%AE%E4%BF%A1%E4%BA%8C%E7%BB%B4%E7%A0%81-1.png?x-oss-process=image/resize,p_50 "微信二维码-1.png")


#### 安装教程

#### 后端安装方法

```
1.  mvn clean package
2.  tar -zxvf hospital-platform-api.tar.gz (解压tar包)
3.  cd hospital-platform-api
5.  sh /sbin/startup.sh dev
```
#### 前端安装方法

```
1.  yarn install (安装node_moudle)
2.  yarn start (启动)
3.  yarn build:pro (构建生产包)
```
