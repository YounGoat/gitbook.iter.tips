#	MySQL

>	MySQL is not the best. It's mine.

##	安装

###	在 Linux 中安装 MySQL Server / MySQL Client

```bash
yum install mysql-server
yum install mysql
```

##	字符集

通过命令行终端登录数据库，如果显示乱码怎么办？

```sql
-- 查看数据表默认字符集
SHOW CREATE TABLE my_table_name;

-- 假设数据表默认字符集为 utf8
SET names utf8;
```
