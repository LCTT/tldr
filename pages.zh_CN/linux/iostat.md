# iostat

> 报告设备和分区的统计信息

- 显示自系统启动以来的 CPU 和磁盘统计数据报告：

`iostat`

- 以兆字节为单位显示 CPU 和磁盘的统计数据报告：

`iostat -m`

- 显示 CPU 统计数据：

`iostat -c`

- 显示磁盘阵列（LVM）的信息：

`iostat -N`

- 显示设备名称为sda的扩展的磁盘统计：

`iostat -xN {{sda}}`

- 每2秒追加显示cpu和磁盘统计报告：

`iostat {{2}}`

[#]: contributors: ([顺势而为]，[jim.大团结]，[∠( ᐛ 」∠)＿]，[王兴宇，Linux 中國]，[马旭]，[Marvin])