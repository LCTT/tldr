# repquota

> 显示某个文件系统下现有的文件限额概况

- 报告所有在用的限额统计：

`sudo repquota -all`

- 报告所有用户的限额统计，即使他们没有使用使用任何限额：

`sudo repquota -v {{filesystem}}`

- 仅报告用户限额：

`repquota --user {{filesystem}}`

- 仅报告用户组限额：

`sudo repquota --group {{filesystem}}`

- 以易读格式报告使用的限额及限制：

`sudo repquota --human-readable {{filesystem}}`

- 以易读格式报告所有用户和组的限额：

`sudo repquota -augs`

[#]: contributors: ([王興與·區塊鏈·Linux中國]，[阿涛])