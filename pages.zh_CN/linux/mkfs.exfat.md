# mkfs.exfat

> 在一个分区内创建一个 exfat 文件系统

- 在设备 b 的分区 1 （`sdb1`）上创建一个 exfat 文件系统：

`mkfs.exfat {{/dev/sdb1}}`

- 创建文件系统时同时设置其卷标：

`mkfs.exfat -n {{volume_name}} {{/dev/sdb1}}`

- 创建文件系统时同时设置其卷 ID：

`mkfs.exfat -i {{volume_id}} {{/dev/sdb1}}`

[#]: contributors: ([王兴宇，Linux & BC])