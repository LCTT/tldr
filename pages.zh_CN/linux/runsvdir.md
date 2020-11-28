# runsvdir

> 运行目录内的所有服务

- 作为当前用户，启用和管理目录下的所有服务：

`runsvdir {{path/to/services}}`

- 作为超级用户，启用和管理目录下的所有服务：

`sudo runsvdir {{path/to/services}}`

- 在单独的会话里启用服务：

`runsvdir -P {{path/to/services}}`

[#]: contributors: ([李峰])