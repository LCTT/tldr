# iperf3

> 用于测试网络带宽的流量发生器

- 将 iperf3 作为服务器运行：

`iperf3 -s`

- 在特定端口上运行 iperf3 服务器：

`iperf3 -s -p {{port}}`

- 开始带宽测试：

`iperf3 -c {{server}}`

- 在多个并行流中运行 iperf3 ：

`iperf3 -c {{server}} -P {{streams}}`

- 反向测试服务器将数据发送到客户端：

`iperf3 -c {{server}} -R`

[#]: contributors: ([潘潘]，[ZMM])