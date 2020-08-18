# smartctl

> 显示磁盘 SMART 数据和其他信息
> 参阅更多信息 https://enwikipediaorg/wiki/SMART

- 显示 SMART 健康摘要：

`sudo smartctl --health {{/dev/sda}}`

- 显示设备信息：

`sudo smartctl --info {{/dev/sda}}`

- 开始快速自检：

`sudo smartctl --test short {{/dev/sda}}`

- 显示当前/最后自检状态和其他 SMART 性能：

`sudo smartctl --capabilities {{/dev/sda}}`

- 显示 SMART 自检日志(如果支持)：

`sudo smartctl --log selftest {{/dev/sda}}`

[#]: contributors: ([jim.大团结])