# netstat

> 显示网络相关的信息例如：打开的链接、打开的 socket 端口，等等

- 列出所有的端口信息：

`netstat -a`

- 列出所有在监听的端口信息：

`netstat -l`

- 列出 TCP 的监听端口信息：

`netstat -t`

- 显示进程的pid和进程名：

`netstat -p`

- 持续列出网络状态：

`netstat -c`

- 列出路由表信息并且不查询主机名：

`netstat -rn`

- 列出正在监听的 TCP 和 UDP 端口（root 身份运行该命令还会同时列出用户和进程）：

`netstat -lepunt`

- 列出路由表信息：

`netstat -nr`

[#]: contributors: ([Phoenix、]，[Cold]，[王兴宇，Linux 中國]，[jrg]，[Rhys])