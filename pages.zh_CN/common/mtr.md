# mtr

> 结合了 traceroute 和 ping 的工具

- 跟踪到主机并持续 ping 所有中间跃点：

`mtr {{host}}`

- 禁用 IP 地址和主机名映射：

`mtr -n {{host}}`

- 每跳 ping 10 次后生成输出：

`mtr -w {{host}}`

- 强制使用 IPv4 , -6 强制使用 IPV6：

`mtr -4 {{host}}`

- 在发送下一个同跳的包前等待给定的时间间隔(秒为单位)：

`mtr -i {{seconds}} {{host}}`

[#]: contributors: ([yoke88]，[Datura stramonium L.])