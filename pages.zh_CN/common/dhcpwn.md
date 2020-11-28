# dhcpwn

> 测试 DHCP IP 耗尽攻击，并嗅探本地 DHCP 流量

- 使用 IP 请求充斥网络：

`dhcpwn --interface {{network_interface}} flood --count {{number_of_requests}}`

- 嗅探本地 DHCP 流量：

`dhcpwn --interface {{network_interface}} sniff`

[#]: contributors: ([潘潘])