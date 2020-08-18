# pvcreate

> 初始化物理卷（磁盘或者分区）以备逻辑卷管理器（LVM）使用

- 初始化 {{/dev/sda1}} 卷以用于 LVM：

`pvcreate {{/dev/sda1}}`

- 强制创建而无任何确认提示：

`pvcreate --force {{/dev/sda1}}`

[#]: contributors: ([王兴宇，Linux & BC]，[杨雪枫])