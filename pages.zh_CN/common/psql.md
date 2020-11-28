# psql

> PostgreSQL 命令行客户端

- 连接数据库使用当前登陆账号做为默认用户连接到本地服务器，默认端口号为5432：

`psql {{database}}`

- 在指定服务器上，通过指定端口和指定用户免密连接数据库：

`psql -h {{host}} -p {{port}} -U {{username}} {{database}}`

- 连接数据库，提示用户输入密码：

`psql -h {{host}} -p {{port}} -U {{username}} -W {{database}}`

- 在指定数据库执行单条SQL查询或PostgreSQL命令（实用的shell 脚本）：

`psql -c '{{query}}' {{database}}`

- 对指定数据库执行脚本命令：

`psql {{database}} -f {{file.sql}}`

[#]: contributors: ([李峰])