# mysqldump

> 备份MySQL数据库
> 主页: <https://devmysqlcom/doc/refman/en/mysqldumphtml>

- 创建备份，用户需要输入密码：

`mysqldump -u {{user}} --password {{database_name}} -r {{filename.sql}}`

- 恢复备份，用户需要输入密码：

`mysql -u {{user}} --password -e "source {{filename.sql}}" {{database_name}}`

[#]: contributors: ([潘潘]，[木子立青])