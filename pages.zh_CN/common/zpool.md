# zpool

> ZFS 池的管理工具

- 查询 ZFS 池的配置与状态：

`zpool status`

- 手动执行 ZFS 池扫描，计算数据校验和并自动纠正数据位错误：

`zpool scrub {{pool_name}}`

- 列出可导入的存储池：

`zpool import`

- 导入一个存储池：

`zpool import {{pool_name}}`

- 导出一个存储池：

`zpool export {{pool_name}}`

- 显示所有存储池操作历史：

`zpool history {{pool_name}}`

- 创建镜像池：

`zpool create {{pool_name}} mirror {{disk1}} {{disk2}} mirror {{disk3}} {{disk4}}`

- 添加一个缓存（L2ARC 二级缓存）：

`zpool add {{pool_name}} cache {{cache_disk}}`

[#]: contributors: ([尚卓燃]，[Datura stramonium L.]，[Jangrui]，[󠀀]，[ㅤ]，[one])