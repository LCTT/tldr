# eject

> 弹出光盘、软驱和磁带设备

- 显示默认的设备：

`eject -d`

- 弹出默认设备：

`eject`

- 弹出默认设备（默认顺序为光驱、SCSI 设备、软驱和磁带）：

`eject {{/dev/cdrom}}`

- 弹出或收入设备的托盘：

`eject -T {{/dev/cdrom}}`

- 弹出光盘：

`eject -r {{/dev/cdrom}}`

- 弹出软驱：

`eject -f {{/mnt/floppy}}`

- 弹出磁带：

`eject -q {{/mnt/tape}}`

[#]: contributors: ([王兴宇，Linux & BC]，[Mr. Ren])