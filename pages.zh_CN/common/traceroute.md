# traceroute

> 打印跟踪网络主机的路由包

- 路由跟踪到主机：

`traceroute {{host}}`

- 禁用IP地址和主机名映射：

`traceroute -n {{host}}`

- 指定响应的等待时间：

`traceroute -w {{0.5}} {{host}}`

- 指定每跳查询的数量：

`traceroute -q {{5}} {{host}}`

- 指定探测包的大小（字节为单位）：

`traceroute {{host}} {{42}}`

[#]: contributors: ([启威])