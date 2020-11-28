# nmap

> 网络探测工具和安全/端口扫描器
> 某些功能仅在 Nmap 以超级权限运行时才可激活
> 主页: <https://nmaporg>

- 尝试确定指定的主机是否已启动以及它们的名称是什么：

`nmap -sn {{ip_or_hostname}} {{optional_another_address}}`

- 尝试确定指定的主机是否已启动并显示其名称，对于存活主机以 TCP 方式扫描编号1-1000的端口：

`nmap {{ip_or_hostname}} {{optional_another_address}}`

- 探测目标主机的运行脚本、服务、操作系统指纹以及跟踪路由：

`nmap -A {{address_or_addresses}}`

- 网络连接良好，将加快执行速度：

`nmap -T4 {{address_or_addresses}}`

- 扫描列表中的特定端口（使用-p- 扫描所有端口1-65535）：

`nmap -p {{port1,port2,…,portN}} {{address_or_addresses}}`

- 执行TCP和UDP扫描（针对UDP仅使用-sU，针对SCTP使用-sZ，针对IP使用-sO）：

`nmap -sSU {{address_or_addresses}}`

- 对主机执行TLS密码扫描，以确定支持的密码和SSL / TLS协议：

`nmap --script ssl-enum-ciphers {{address_or_addresses}} -p 443`

[#]: contributors: ([绝洛]，[颉]，[Datura stramonium L.])