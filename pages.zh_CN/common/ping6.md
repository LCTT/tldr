# ping6

> 通过 IPv 6 地址向网络主机发送 ICMP ECHO_REQUEST 数据包

- Ping 一个主机：

`ping6 {{host}}`

- 仅使用特定次数（｛｛count｝｝内的数值） ping 一个主机：

`ping6 -c {{count}} {{host}}`

- 在指定请求之间的间隔（以秒为单位） Ping 一个主机（默认值为1秒）：

`ping6 -i {{seconds}} {{host}}`

- ping 主机时不查找该地址的符号名：

`ping6 -n {{host}}`

- ping 一个主机，当收到包时响铃（如果终端支持）：

`ping6 -a {{host}}`

[#]: contributors: ([王興與]，[Nonamev]，[jim.大团结])