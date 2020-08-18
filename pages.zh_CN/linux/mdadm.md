# mdadm

> RAID 管理工具

- 创建阵列：

`mdadm --create {{/path/to/raid_device_file}} --level {{raid_level}} --raid-devices {{number_of_disks}} {{/path/to/disk_device_file}}`

- 停止阵列：

`mdadm -S {{/path/to/raid_device_file}}`

- 标记磁盘为失效：

`mdadm {{/path/to/raid_device_file}} -f {{/path/to/disk_device_file}}`

- 移除磁盘：

`mdadm {{/path/to/raid_device_file}} -r {{/path/to/disk_device_file}}`

- 添加磁盘到阵列：

`mdadm {{/path/to/raid_device_file}} -a {{/path/to/disk_device_file}}`

- 显示 RAID 信息：

`mdadm -D {{/path/to/raid_device_file}}`

[#]: contributors: ([王兴宇，Linux 中國])