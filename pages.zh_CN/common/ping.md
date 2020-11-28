# ping

> 向网络主机发送 ICMP 回声请求数据包

- Ping 主机：

`ping {{主机}}`

- Ping 主机给定次数：

`ping -c {{count}} {{host}}`

- Ping 主机，指定请求间隔秒数（默认1秒）：

`ping -i {{seconds}} {{host}}`

- Ping主机，但不尝试查找地址的符号名：

`ping -n {{host}}`

- 当收到数据包时，ping 主机并响铃（如果您的终端支持）：

`ping -a {{host}}`

- 如果没有收到响应，也会显示一条消息：

`ping -O {{host}}`

[#]: contributors: ([陌影]，[王興與]，[晨曦]，[王兴宇，Linux & BC]，[MISS]，[孙佳林]，[AEIOU]，[白宦成]，[　　　　　　　　])