# Database知识

## MySQL

### 创建数据库
DROP DATABASE IF EXISTS `db_name`;

CREATE DATABASE `db_name` CHARACTER SET 'utf8' COLLATE'utf8_general_ci';

USE `db_name`;

### 刷新权限
GRANT ALL PRIVILEGES ON *.* TO 'root'@'%' IDENTIFIED BY 'password' with GRANT OPTION;

FLUSH privileges;