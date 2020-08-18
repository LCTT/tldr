# iptables

> 用来配置由linux内核防火墙提供的表、链和规则的程序

- 查看所有表的链、规则和包/字节计数器：

`sudo iptables -vnL`

- 设置链的规则：

`sudo iptables -P {{chain}} {{rule}}`

- 在链尾追加针对ip的规则：

`sudo iptables -A {{chain}} -s {{ip}} -j {{rule}}`

- 根据协议和端口在链策略尾部追加针对ip的规则：

`sudo iptables -A {{chain}} -s {{ip}} -p {{protocol}} --dport {{port}} -j {{rule}}`

- 删除链规则：

`sudo iptables -D {{chain}} {{rule_line_number}}`

- 将指定表的iptables配置保存到文件：

`sudo iptables-save -t {{tablename}} > {{path/to/iptables_file}}`

- 从文件中恢复iptables配置：

`sudo iptables-restore < {{path/to/iptables_file}}`

[#]: contributors: ([jrg])