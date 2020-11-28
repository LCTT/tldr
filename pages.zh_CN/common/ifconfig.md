# ifconfig

> 网络接口配置工具(此工具已经不再维护，可以考虑移步 ip 命令)

- 查看一个以太网适配器的网络设置、数据包情况：

`ifconfig eth0`

- 显示所有接口的详细信息，包括禁用的接口：

`ifconfig -a`

- 禁用 eth0 ：

`ifconfig eth0 down`

- 启用 eth0 ：

`ifconfig eth0 up`

- 将IP地址分配给 eth0 接口：

`ifconfig eth0 {{ip_address}}`

[#]: contributors: ([公孙林]，[王兴宇]，[Datura stramonium L.])