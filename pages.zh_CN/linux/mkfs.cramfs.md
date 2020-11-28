# mkfs.cramfs

> 在一个分区上创建一个ROM文件系统

- 在设备b分区1上创建一个ROM文件系统：

`mkfs.cramfs {{/dev/sdb1}}`

- 创建一个有卷名的ROM文件系统：

`mkfs.cramfs -n {{volume_name}} {{/dev/sdb1}}`

[#]: contributors: ([阿涛])