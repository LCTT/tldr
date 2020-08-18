# badblocks

> 在设备中搜索损坏区块
> badblocks 的某些用法可能导致破坏性操作，例如删除磁盘上的所有数据，包括分区表

- 使用非破坏性只读测试搜索磁盘中的损坏区块：

`sudo badblocks {{/dev/sda}}`

- 使用非破坏性读写测试在未安装的磁盘上搜索损坏区块：

`sudo badblocks -n {{/dev/sda}}`

- 使用破坏性写入测试在未安装的磁盘上搜索损坏区块：

`sudo badblocks -w {{/dev/sda}}`

[#]: contributors: ([Datura stramonium L.])