# 整合spring+mybatis

> change 1
> change 2

> 使用前，需执行提供的sql脚本
> 更改jdbc.properties文件


# 主要配置文件
1. pom.xml
2. web.xml
3. beans-*.xml


# 包含主要页面
1. /
2. /users
3. /user/new
4. /user/edit



# sql 语句


> create database demohot_demos default charset=utf8;
> create table demos.`user` ( `user_id` bigint(20) NOT NULL AUTO_INCREMENT, `username` varchar(255), `age` int, `user_type` int, PRIMARY KEY (`user_id`));
> create table demos.demo( demo_id bigint not null auto_increment, title varchar(255), content varchar(10000), demo_type int, primary key(demo_id));

数据库密码配置
src/main/resources/jdbc.properties
默认配置
> jdbc.username = root
> jdbc.password = 123456
