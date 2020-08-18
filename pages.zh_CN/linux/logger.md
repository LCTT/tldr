# logger

> 添加一条信息到 syslog (/var/log/syslog)

- 记录一条消息到系统日志：

`logger {{message}}`

- 从标准输入获取并写入ｓｙｓｌｏｇ：

`echo {{log_entry}} | logger`

- 将输出发送至运行的远程 syslog 服务在给定的端口默认端口 514：

`echo {{log_entry}} | logger --server {{hostname}} --port {{port}}`

- 对每一行使用指定的标志默认是登录用户名：

`echo {{log_entry}} | logger --tag {{tag}}`

- 记录具有给定优先级的消息默认值是 `user.note`所有优先级选项见 `man logger`：

`echo {{log_entry}} | logger --priority {{user.warning}}`

[#]: contributors: ([ ]，[jim.大团结]，[hjj])