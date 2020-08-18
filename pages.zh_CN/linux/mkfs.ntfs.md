# mkfs.ntfs

> 在一分区内创建NTFS文件系统

- 在sdb1的分区1内创建NTFS文件系统：

`mkfs.ntfs {{/dev/sdb1}}`

- 使用卷标签创建文件系统：

`mkfs.ntfs -L {{volume_label}} {{/dev/sdb1}}`

- 以指定的UUID创建文件系统：

`mkfs.ntfs -U {{UUID}} {{/dev/sdb1}}`

[#]: contributors: ([Judie]，[盛曦 姜])