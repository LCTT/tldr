# shutdown

> 关闭或者重新启动系统

- 立即关闭电源（停机）：

`shutdown -h now`

- 立即重启：

`shutdown -r now`

- 5分钟后重启：

`shutdown -r +{{5}} &`

- 在下午1点关机（-h参数使用24小时制）：

`shutdown -h 13:00`

- 取消预定的定时关机操作：

`shutdown -c`

[#]: contributors: ([Datura stramonium L.]，[仁人]，[李桥])