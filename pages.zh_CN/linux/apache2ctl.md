# apache2ctl

> 用于管理 HTTP Web 服务器 Apache 的命令行工具
> 基于 debian 的操作系统带有这个命令，对于基于 RHEL 的操作系统，请参见 “ httpd ”

- 启动 apache 守护进程如果其已在运行，则抛出一个信息：

`sudo apache2ctl start`

- 停止 Apache 守护进程：

`sudo apache2ctl stop`

- 重新启动 Apache 守护进程：

`sudo apache2ctl restart`

- 测试配置文件的语法：

`sudo apache2ctl -t`

- 列出加载的模块：

`sudo apache2ctl -M`

[#]: contributors: ([Datura stramonium L.])