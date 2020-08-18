# cpufreq-aperf

> 计算一段时间内的平均 CPU 频率
> 需要 root 权限

- 开始计算，默认为所有 cpu 核心和 1 秒刷新间隔：

`sudo cpufreq-aperf`

- 只对 CPU 1 开始计算：

`sudo cpufreq-aperf -c {{1}}`

- 开始计算所有 cpu 核心并间隔 3 秒刷新：

`sudo cpufreq-aperf -i {{3}}`

- 只计算一次：

`sudo cpufreq-aperf -o`

[#]: contributors: ([jim.大团结])