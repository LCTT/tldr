# ip

> 显示/操纵 路由、网络设备、策略路由和隧道

- 列出接口的详细信息：

`ip a`

- 列出路由表：

`ip r`

- 显示网络邻居(arp表)：

`ip n`

- 启动/关闭 某个接口：

`ip link set {{interface}} up/down`

- 增加/删除 接口的ip地址：

`ip addr add/del {{ip}}/{{mask}} dev {{interface}}`

- 添加默认路由：

`ip route add default via {{ip}} dev {{interface}}`

[#]: contributors: ([jrg])