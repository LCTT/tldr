# route 

> route 命令用于设置路由表

- 显示路由表信息：

`route -n`

- 添加路由规则：

`sudo route add -net {{ip_address}} netmask {{netmask_address}} gw {{gw_address}}`

- 删除路由规则：

`sudo route del -net {{ip_address}} netmask {{netmask_address}} dev {{gw_address}}`

[#]: contributors: ([SuWei])