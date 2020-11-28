# mysql

> MySQL命令行工具
> 主页：<https://wwwmysqlcom/>

- 连接数据库：

`mysql {{database_name}}`

- 连接数据库，指定用户及密码：

`mysql -u {{user}} --password {{database_name}}`

- 连接另一主机的数据库：

`mysql -h {{database_host}} {{database_name}}`

- 通过Unix socket模式连接数据库：

`mysql --socket {{path/to/socket.sock}}`

- 在脚本文件（批处理文件）中执行SQL语句：

`mysql -e "source {{filename.sql}}" {{database_name}}`

[#]: contributors: ([潘潘]，[木子立青])