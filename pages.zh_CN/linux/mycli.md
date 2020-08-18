# mycli

> MySQL 的命令行工具，支持 MariaDB 和 Percona 语法高亮和自动补全

- 使用当前登录的用户连接到数据库：

`mycli {{database_name}}`

- 使用指定的用户连接到数据库：

`mycli -u {{user}} {{database_name}}`

- 使用指定的用户连接到指定主机上的数据库：

`mycli -u {{user}} -h {{host}} {{database_name}}`

[#]: contributors: ([Datura stramonium L.])