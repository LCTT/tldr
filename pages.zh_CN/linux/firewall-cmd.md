# firewall-cmd

> Firewalld 的命令行客户端

- 查看可用的防火墙区域：

`firewall-cmd --get-active-zones`

- 查看当前已启用的规则：

`firewall-cmd --list-all`

- 开放特定区域的服务端口：

`firewall-cmd --permanent --zone={{public}} --add-service={{https}}`

- 阻止特定区域的服务端口活动：

`firewall-cmd --permanent --zone={{public}} --remove-service={{http}}`

- 重新加载以使新规则生效：

`firewall-cmd --reload`

[#]: contributors: ([Mr. Ren])