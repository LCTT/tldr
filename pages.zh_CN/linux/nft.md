# nft

> 允许配置 Linux 内核防火墙提供的表，链和规则
> Nftables 取代了 iptables 

- 查看当前配置：

`sudo nft list ruleset`

- 添加一个带有 inet 系列和表 filter 的新表：

`sudo nft add table {{inet}} {{filter}}`

- 添加新链以接受所有入站流量：

`sudo nft add chain {{inet}} {{filter}} {{input}} \{ type {{filter}} hook {{input}} priority {{0}} \; policy {{accept}} \}`

- 添加一条规则允许多个 TCP 端口流量：

`sudo nft add rule {{inet}} {{filter}} {{input}} {{tcp}} {{dport \{ telnet, ssh, http, https \} accept}}`

- 显示规则句柄：

`sudo nft --handle --numeric list chain {{family}} {{table}} {{chain}}`

- 删除一条规则：

`sudo nft delete rule {{inet}} {{filter}} {{input}} handle {{3}}`

- 保存当前配置：

`sudo nft list ruleset > {{/etc/nftables.conf}}`

[#]: contributors: ([潘潘]，[Mr. Ren])