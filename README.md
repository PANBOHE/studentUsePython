# studentUsePython

基于python+django+vue.js开发的学生信息管理系统
用于初学者学习和演练


### 功能介绍

平台采用B/S结构，后端采用主流的Python语言进行开发，前端采用主流的Vue.js进行开发。

功能包括：学生管理、班级管理、用户管理、日志管理、系统信息模块。



### 代码结构

- server目录是后端代码
- web目录是前端代码

### 部署运行

#### 后端运行步骤
(1) 安装python 3.8

(2) 安装依赖。进入server目录下，执行 pip install -r requirements.txt

(3) 安装mysql 5.7数据库，并创建数据库，命名为xxx，创建SQL如下：
```
CREATE DATABASE IF NOT EXISTS xxx DEFAULT CHARSET utf8 COLLATE utf8_general_ci
```
(4) 恢复xxx.sql数据。在mysql下依次执行如下命令：

```
mysql> use xxx;
mysql> source D:/xxx/xxx/xxx.sql;
```

(5) 启动django服务。在server目录下执行：
```
python manage.py runserver
```
