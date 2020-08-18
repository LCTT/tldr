# mkfs.fat

> 在分区内创建 MS-DOS 文件系统

- 在设备 b（ sdb1 ）上的分区 1 内创建一个 FAT 文件系统：

`mkfs.fat {{/dev/sdb1}}`

- 使用卷名创建文件系统：

`mkfs.fat -n {{volume_name}} {{/dev/sdb1}}`

- 使用 volume-id 创建文件系统：

`mkfs.fat -i {{volume_id}} {{/dev/sdb1}}`

- 使用 5 个而不是 2 个文件分配表：

`mkfs.fat -f 5 {{/dev/sdb1}}`

[#]: contributors: ([潘潘]，[玉叶])