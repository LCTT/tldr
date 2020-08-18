# bmon

> 监视带宽并捕获与网络相关的统计信息

- 显示所有接口列表：

`bmon -a`

- 用 bps 显示数据传输速率：

`bmon -b`

- 设置策略以定义显示哪个网络接口：

`bmon -p {{interface_1,interface_2,interface_3}}`

- 设置以秒为单位的间隔，各个计数器就是以此间隔计算的：

`bmon -R {{2.0}}`

[#]: contributors: ([潘潘]，[jim.大团结]，[Judie])