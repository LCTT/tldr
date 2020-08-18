# cpufreq-info

> 显示 CPU 频率信息的工具

- 显示所有 CPU 的频率信息：

`cpufreq-info`

- 显示指定 CPU 的 CPU 频率信息：

`cpufreq-info -c {{cpu_number}}`

- 显示允许的最小和最大 CPU 频率：

`cpufreq-info -l`

- 以表格格式显示当前最小和最大的 CPU 频率和策略：

`cpufreq-info -o`

- 显示可用的 CPU 频率策略：

`cpufreq-info -g`

- 根据 cpufreq 内核模块，以人类可读的格式显示当前CPU 工作频率：

`cpufreq-info -f -m`

- 通过从硬件读取，以人类可读的格式显示当前 CPU 工作频率（仅适用于 root ）：

`sudo cpufreq-info -w -m`

[#]: contributors: ([琳小梁]，[玉堂白鹤])