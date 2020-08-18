# arp-scan

> 发送 ARP 包到主机（指定 IP 地址或主机名）以扫描本地网络

- 扫描当前本地网络：

`arp-scan --localnet`

- 使用自定义位掩码扫描 IP 网络：

`arp-scan {{192.168.1.1}}/{{24}}`

- 扫描自定义范围内的 IP 网络：

`arp-scan {{127.0.0.0}}-{{127.0.0.31}}`

- 使用自定义网络掩码扫描 IP 网络：

`arp-scan {{10.0.0.0}}:{{255.255.255.0}}`

[#]: contributors: ([琳小梁]，[Datura stramonium L.])