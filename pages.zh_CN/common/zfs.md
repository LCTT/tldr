# zfs

> 管理 ZFS 文件系统

- 列出所有可用的 zfs 文件系统：

`zfs list`

- 创建一个新的 ZFS 文件系统：

`zfs create {{pool_name/filesystem_name}}`

- 删除一个 ZFS 文件系统：

`zfs destroy {{pool_name/filesystem_name}}`

- 创建一个ZFS 文件系统快照：

`zfs snapshot {{pool_name/filesystem_name}}@{{snapshot_name}}`

- 在指定文件系统上启用压缩：

`zfs set compression=on {{pool_name/filesystem_name}}`

- 改变一个文件系统的挂载点：

`zfs set mountpoint={{/my/mount/path}} {{pool_name/filesystem_name}}`

[#]: contributors: ([东先生]，[Amor])