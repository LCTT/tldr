# salt

> 在远程 salt 下级上执行命令或定义其状态

- 列出所有连接的下级：

`salt '*' test.ping`

- 在所有连接的下级上执行全局状态：

`salt '*' state.highstate`

- 在一个下级子集里使用操作系统的包管理器（apt、yum、brew）升级软件包：

`salt '*.domain.com' pkg.upgrade`

- 在特定的下级执行某个命令：

`salt '{{minion_id}}' cmd.run "ls "`

[#]: contributors: ([硬核老王（📺Linux中国）]，[咖啡])