# iperf

> 测量电脑间的网络带宽

- 在服务器端启动：

`iperf -s`

- 在客户端上启动：

`iperf -c {{server_address}}`

- 在客户端上启动，使用 5 个线程：

`iperf -c {{server_address}} -P {{5}}`

[#]: contributors: ([蔚然]，[庄秋彬])