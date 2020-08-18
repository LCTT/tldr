# service

> 通过运行 init 脚本来管理服务
> 应省略完整的脚本路径（/etc/initd/ 是假定缺省的）

- 启动/停止/重新启动/重新加载服务（启动/停止始终可用）：

`service {{init_script}} {{start|stop|restart|reload}}`

- 执行完全重新启动（用 start 和 stop 运行脚本）：

`service {{init_script}} --full-restart`

- 显示服务的当前状态：

`service {{init_script}} status`

- 列出所有服务的状态：

`service --status-all`

[#]: contributors: ([王兴宇]，[Datura stramonium L.])