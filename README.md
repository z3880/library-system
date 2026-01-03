# 图书馆管理系统（Servlet+JSP版）
## 项目说明
本项目为**软件工程课程作业**，基于Java Servlet+JSP+DBUtil+MySQL开发，实现高校图书馆图书管理、读者借阅、还书等核心功能，适配Eclipse+Tomcat开发环境。

## 一、技术栈说明
- 后端核心：Java Servlet 3.0 + JSP + JDBC + 自定义DBUtil数据库工具类
- 数据库：MySQL 8.0
- 开发工具：Eclipse IDE + Tomcat 9.0
- 前端技术：HTML+CSS+JavaScript + EL表达式 + JSTL标签库
- 安全机制：MD5密码加密存储 + Session用户身份校验与权限控制

## 二、环境部署与运行步骤（老师可直接本地启动）
### ✅ 前置环境要求
1. 本地安装：JDK 1.8 及以上、MySQL 8.0、Tomcat 9.0、Eclipse IDE；
2. 数据库准备：打开Navicat/MySQL命令行，创建数据库 `library_db`，执行项目内SQL脚本完成表初始化。

### ✅ 本地运行步骤
1. 打开Eclipse，将项目导入（File → Import → Existing Projects into Workspace）；
2. 配置Tomcat 9.0服务器：Eclipse → Window → Preferences → Server → Runtime Environments，添加本地Tomcat；
3. 修改数据库配置：打开项目中 `com.library.util.DBUtil` 类，替换MySQL账号、密码为本地配置；
4. 启动项目：右键项目 → Run As → Run on Server → 选择配置好的Tomcat，点击Finish；
5. 访问系统：浏览器输入地址 `http://localhost:8080/library-system/login.jsp` 即可进入登录页。

## 三、测试账号（直接可用）
- 🔧 管理员账号：admin  |  密码：123456
  权限：图书入库、图书修改/下架、全量图书/借阅记录查看
- 📖 普通读者账号：user01  |  密码：123456
  权限：图书查询、图书借阅、图书还书、个人借阅记录查看

## 四、核心功能模块
### ✅ 管理员功能
1. 管理员专属登录与权限校验；
2. 图书全生命周期管理：新增入库、信息修改、库存调整、图书下架；
3. 全局数据查看：所有图书信息、全馆借阅记录查看。

### ✅ 普通读者功能
1. 读者账号注册、登录、身份校验；
2. 图书精准检索：支持书名、ISBN、作者模糊查询，展示图书库存与可借状态；
3. 图书借阅：自动校验库存、拦截重复借阅，生成借阅记录；
4. 图书还书：自动恢复图书库存、更新归还时间，完成借阅流程；
5. 个人中心：查看本人未归还/已归还借阅记录，支持单本还书操作。

## 五、项目目录结构（与Eclipse项目完全一致）
# 图书馆管理系统（Servlet+JSP版）
## 项目说明
本项目为**软件工程课程作业**，基于Java Servlet+JSP+DBUtil+MySQL开发，实现高校图书馆图书管理、读者借阅、还书等核心功能，适配Eclipse+Tomcat开发环境。

## 一、技术栈说明
- 后端核心：Java Servlet 3.0 + JSP + JDBC + 自定义DBUtil数据库工具类
- 数据库：MySQL 8.0
- 开发工具：Eclipse IDE + Tomcat 9.0
- 前端技术：HTML+CSS+JavaScript + EL表达式 + JSTL标签库
- 安全机制：MD5密码加密存储 + Session用户身份校验与权限控制

## 二、环境部署与运行步骤（老师可直接本地启动）
### ✅ 前置环境要求
1. 本地安装：JDK 1.8 及以上、MySQL 8.0、Tomcat 9.0、Eclipse IDE；
2. 数据库准备：打开Navicat/MySQL命令行，创建数据库 `library_db`，执行项目内SQL脚本完成表初始化。

### ✅ 本地运行步骤
1. 打开Eclipse，将项目导入（File → Import → Existing Projects into Workspace）；
2. 配置Tomcat 9.0服务器：Eclipse → Window → Preferences → Server → Runtime Environments，添加本地Tomcat；
3. 修改数据库配置：打开项目中 `com.library.util.DBUtil` 类，替换MySQL账号、密码为本地配置；
4. 启动项目：右键项目 → Run As → Run on Server → 选择配置好的Tomcat，点击Finish；
5. 访问系统：浏览器输入地址 `http://localhost:8080/library-system/login.jsp` 即可进入登录页。

## 三、测试账号（直接可用）
- 🔧 管理员账号：admin  |  密码：123456
  权限：图书入库、图书修改/下架、全量图书/借阅记录查看
- 📖 普通读者账号：user01  |  密码：123456
  权限：图书查询、图书借阅、图书还书、个人借阅记录查看

## 四、核心功能模块
### ✅ 管理员功能
1. 管理员专属登录与权限校验；
2. 图书全生命周期管理：新增入库、信息修改、库存调整、图书下架；
3. 全局数据查看：所有图书信息、全馆借阅记录查看。

### ✅ 普通读者功能
1. 读者账号注册、登录、身份校验；
2. 图书精准检索：支持书名、ISBN、作者模糊查询，展示图书库存与可借状态；
3. 图书借阅：自动校验库存、拦截重复借阅，生成借阅记录；
4. 图书还书：自动恢复图书库存、更新归还时间，完成借阅流程；
5. 个人中心：查看本人未归还/已归还借阅记录，支持单本还书操作。

## 五、项目目录结构（与Eclipse项目完全一致）# 图书馆管理系统（Servlet+JSP版）
## 项目说明
本项目为**软件工程课程作业**，基于Java Servlet+JSP+DBUtil+MySQL开发，实现高校图书馆图书管理、读者借阅、还书等核心功能，适配Eclipse+Tomcat开发环境。

## 一、技术栈说明
- 后端核心：Java Servlet 3.0 + JSP + JDBC + 自定义DBUtil数据库工具类
- 数据库：MySQL 8.0
- 开发工具：Eclipse IDE + Tomcat 9.0
- 前端技术：HTML+CSS+JavaScript + EL表达式 + JSTL标签库
- 安全机制：MD5密码加密存储 + Session用户身份校验与权限控制

## 二、环境部署与运行步骤（老师可直接本地启动）
### ✅ 前置环境要求
1. 本地安装：JDK 1.8 及以上、MySQL 8.0、Tomcat 9.0、Eclipse IDE；
2. 数据库准备：打开Navicat/MySQL命令行，创建数据库 `library_db`，执行项目内SQL脚本完成表初始化。

### ✅ 本地运行步骤
1. 打开Eclipse，将项目导入（File → Import → Existing Projects into Workspace）；
2. 配置Tomcat 9.0服务器：Eclipse → Window → Preferences → Server → Runtime Environments，添加本地Tomcat；
3. 修改数据库配置：打开项目中 `com.library.util.DBUtil` 类，替换MySQL账号、密码为本地配置；
4. 启动项目：右键项目 → Run As → Run on Server → 选择配置好的Tomcat，点击Finish；
5. 访问系统：浏览器输入地址 `http://localhost:8080/library-system/login.jsp` 即可进入登录页。

## 三、测试账号（直接可用）
- 🔧 管理员账号：admin  |  密码：123456
  权限：图书入库、图书修改/下架、全量图书/借阅记录查看
- 📖 普通读者账号：user01  |  密码：123456
  权限：图书查询、图书借阅、图书还书、个人借阅记录查看

## 四、核心功能模块
### ✅ 管理员功能
1. 管理员专属登录与权限校验；
2. 图书全生命周期管理：新增入库、信息修改、库存调整、图书下架；
3. 全局数据查看：所有图书信息、全馆借阅记录查看。

### ✅ 普通读者功能
1. 读者账号注册、登录、身份校验；
2. 图书精准检索：支持书名、ISBN、作者模糊查询，展示图书库存与可借状态；
3. 图书借阅：自动校验库存、拦截重复借阅，生成借阅记录；
4. 图书还书：自动恢复图书库存、更新归还时间，完成借阅流程；
5. 个人中心：查看本人未归还/已归还借阅记录，支持单本还书操作。

## 五、项目目录结构（与Eclipse项目完全一致）
# 图书馆管理系统（Servlet+JSP版）
## 项目说明
本项目为**软件工程课程作业**，基于Java Servlet+JSP+DBUtil+MySQL开发，实现高校图书馆图书管理、读者借阅、还书等核心功能，适配Eclipse+Tomcat开发环境。

## 一、技术栈说明
- 后端核心：Java Servlet 3.0 + JSP + JDBC + 自定义DBUtil数据库工具类
- 数据库：MySQL 8.0
- 开发工具：Eclipse IDE + Tomcat 9.0
- 前端技术：HTML+CSS+JavaScript + EL表达式 + JSTL标签库
- 安全机制：MD5密码加密存储 + Session用户身份校验与权限控制

## 二、环境部署与运行步骤（老师可直接本地启动）
### ✅ 前置环境要求
1. 本地安装：JDK 1.8 及以上、MySQL 8.0、Tomcat 9.0、Eclipse IDE；
2. 数据库准备：打开Navicat/MySQL命令行，创建数据库 `library_db`，执行项目内SQL脚本完成表初始化。

### ✅ 本地运行步骤
1. 打开Eclipse，将项目导入（File → Import → Existing Projects into Workspace）；
2. 配置Tomcat 9.0服务器：Eclipse → Window → Preferences → Server → Runtime Environments，添加本地Tomcat；
3. 修改数据库配置：打开项目中 `com.library.util.DBUtil` 类，替换MySQL账号、密码为本地配置；
4. 启动项目：右键项目 → Run As → Run on Server → 选择配置好的Tomcat，点击Finish；
5. 访问系统：浏览器输入地址 `http://localhost:8080/library-system/login.jsp` 即可进入登录页。

## 三、测试账号（直接可用）
- 🔧 管理员账号：admin  |  密码：123456
  权限：图书入库、图书修改/下架、全量图书/借阅记录查看
- 📖 普通读者账号：user01  |  密码：123456
  权限：图书查询、图书借阅、图书还书、个人借阅记录查看

## 四、核心功能模块
### ✅ 管理员功能
1. 管理员专属登录与权限校验；
2. 图书全生命周期管理：新增入库、信息修改、库存调整、图书下架；
3. 全局数据查看：所有图书信息、全馆借阅记录查看。

### ✅ 普通读者功能
1. 读者账号注册、登录、身份校验；
2. 图书精准检索：支持书名、ISBN、作者模糊查询，展示图书库存与可借状态；
3. 图书借阅：自动校验库存、拦截重复借阅，生成借阅记录；
4. 图书还书：自动恢复图书库存、更新归还时间，完成借阅流程；
5. 个人中心：查看本人未归还/已归还借阅记录，支持单本还书操作。

## 五、项目目录结构（与Eclipse项目完全一致）
library-system/├── src/main/java/│ ├── com.library.bean/│ │ ├── Admin.java│ │ ├── Book.java│ │ ├── Reader.java│ │ └── BorrowRecord.java│ ├── com.library.servlet/│ │ ├── AdminLoginServlet.java│ │ ├── ReaderLoginServlet.java│ │ ├── RegisterServlet.java│ │ ├── BookServlet.java│ │ ├── BorrowServlet.java│ │ └── ReturnServlet.java│ └── com.library.util/│ ├── DBUtil.java│ └── MD5Util.java├── WebContent/│ ├── pages/│ │ ├── login.jsp│ │ ├── register.jsp│ │ ├── admin_book.jsp│ │ ├── reader_book.jsp│ │ └── reader_record.jsp│ ├── css/style.css│ ├── js/check.js│ └── index.jsp├── library_db.sql└── README.md
