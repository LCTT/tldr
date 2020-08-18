# quotacheck

> 扫描文件系统检查磁盘使用情况创建、检查和修复配额文件
> 为防止配额文件损失，执行配额检查时最好关闭磁盘配额功能

- 检查挂载的所有非 NFS 文件系统磁盘配额：

`sudo quotacheck --all`

- 强行配额检查，即使磁盘配额处于激活中（可能造成配额文件损失）：

`sudo quotacheck --force {{mountpoint}}`

- 调试模式下检查指定文件系统磁盘配额：

`sudo quotacheck --debug {{mountpoint}}`

- 检查指定文件系统的磁盘配额，显示进度：

`sudo quotacheck --verbose {{mountpoint}}`

- 检查指定用户磁盘配额：

`sudo quotacheck --user {{user}} {{mountpoint}}`

- 检查指定分组磁盘配额：

`sudo quotacheck --group {{group}} {{mountpoint}}`

[#]: contributors: ([李峰])