# pg_ctl

> PostgreSQL 服务端和数据库集群管理工具

- 启用指定的 PostgreSQL 服务端：

`pg_ctl -D {{data_directory}} -l {{log_file_name}}`

- 初始化 PostgreSQL 数据库集群：

`pg_ctl -D {{data_directory}} init`

- 停用指定的 PostgreSQL 服务端：

`pg_ctl -D {{data_directory}} stop`

- 重启指定的 PostgreSQL 服务端：

`pg_ctl -D {{data_directory}} restart`

[#]: contributors: ([李峰])