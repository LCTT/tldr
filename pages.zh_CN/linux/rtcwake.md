# rtcwake

> 进入系统睡眠状态，直到指定相对于你的 BIOS 时钟的唤醒时间
> 需要 39），并在给定的日期和时间唤醒：

- 显示是否设置了警报：

`sudo rtcwake -m show -v`

- 10 秒后停止撞击并唤醒：

`sudo rtcwake -m mem -s {{10}}`

- 挂起到磁盘（更高的省电）并在 15 分钟后唤醒：

`sudo rtcwake -m disk --date +{{15}}min`

- 冻结系统（比暂停到 ram 更有效但需要 linux > 3.9）并在给定的日期和时间唤醒：

`sudo rtcwake -m freeze --date {{YYYYMMDDhhmm}}`

- 禁用先前设置的警报：

`sudo rtc -m disable`

- 执行干运行以在给定时间唤醒计算机 （按Ctrl + C中止）：

`sudo rtcwake -m on --date {{hh:ss}}`

[#]: contributors: ([潘潘])