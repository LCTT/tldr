# journalctl

> 查询 systemd 日志

- 显示自本次系统启动以来的所有日志信息：

`journalctl -b`

- 显示自上次系统启动以来的所有日志信息：

`journalctl -b -1`

- 监视刷新显示最新日志信息（用法和`tail -f`对传统系统日志的操作相似）：

`journalctl -f`

- 按特定单元显示所有消息：

`journalctl -u {{unit}}`

- 通过特定的流程显示所有消息：

`journalctl _PID={{pid}}`

- 通过特定的可执行文件显示所有消息：

`journalctl {{path/to/executable}}`

[#]: contributors: ([威]，[jim.大团结]，[Mr. Ren]，[陈俊龙]，[蜂子🐝ℋ])