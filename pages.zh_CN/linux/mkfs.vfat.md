# mkfs.vfat

> 在分区内创建 MS-DOS 文件系统

- 在设备 b 的分区 1（`sdb1`）上创建一个 vfat 文件系统：

`mkfs.vfat {{/dev/sdb1}}`

- 创建文件系统，并指定卷标：

`mkfs.vfat -n {{volume_name}} {{/dev/sdb1}}`

- 创建文件系统，并指定卷 id：

`mkfs.vfat -i {{volume_id}} {{/dev/sdb1}}`

- 创建文件系统时建立 5 个（而不是 2 个）文件分配表：

`mkfs.vfat -f 5 {{/dev/sdb1}}`

[#]: contributors: ([王兴宇，Linux 中國]，[Datura stramonium L.])