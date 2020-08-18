# mpstat

> 报告 CPU 的统计信息

- 每 2 秒显示一次 CPU 统计信息：

`mpstat {{2}}`

- 以 2 秒的间隔依次显示 5 次 CPU 统计报告：

`mpstat {{2}} {{5}}`

- 以 2 秒为间隔依次显示特定处理器的 5 次 CPU 统计报告：

`mpstat -P {{0}} {{2}} {{5}}`

[#]: contributors: ([lc])