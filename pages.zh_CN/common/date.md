# date

> 设置或者显示系统日期

- 使用默认区域设置的格式显示当前日期：

`date +"%c"`

- 以 UTC 和 ISO 8601 格式显示当前日期：

`date -u +"%Y-%m-%dT%H:%M:%SZ"`

- 将当前日期显示为 Unix 时间戳（从 Unix epoch 开始的秒数）：

`date +%s`

- 使用默认格式显示特定日期（表示为 Unix 时间戳）：

`date -d @1473305798`

- 将特定日期转换为 Unix 时间戳格式：

`date -d "{{2018-09-01 00:00}}" +%s --utc`

[#]: contributors: ([Datura stramonium L.]，[jrg])