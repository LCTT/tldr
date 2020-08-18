# redis-cli

> 打开一个连接到 Redis 服务的命令行工具

- 连接到本地服务：

`redis-cli`

- 用默认端口（6379）连接到远端服务器：

`redis-cli -h {{host}}`

- 用指定端口连接到远端服务器：

`redis-cli -h {{host}} -p {{port}}`

- 指定一个密码：

`redis-cli -a {{password}}`

- 执行 Redis 命令：

`redis-cli {{redis_command}}`

[#]: contributors: ([松果]，[hollowJ丶])