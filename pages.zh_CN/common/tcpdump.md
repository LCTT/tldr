# tcpdump

> 在网络上转储流量

- 列出系统中可以用tcpdump捕包的网络接口：

`tcpdump -D`

- 捕获指定网络接口的流量：

`tcpdump -i {{eth0}}`

- 捕获所有TCP包，并以ASICII格式打印：

`tcpdump -A tcp`

- 捕获流经指定主机的流量：

`tcpdump host {{www.example.com}}`

- 指定eth0端口，源ip 192.168.1.1 和 目的地址 192.168.1.2的80端口：

`tcpdump -i {{eth0}} src {{192.168.1.1}} and dst {{192.168.1.2}} and dst port {{80}}`

- 捕获指定网段的流量：

`tcpdump net {{192.168.1.0/24}}`

- 捕获不经过 22 端口的流量，并写入文件：

`tcpdump -w {{dumpfile.pcap}} not port {{22}}`

- 从指定文件读取数据包：

`tcpdump -r {{dumpfile.pcap}}`

[#]: contributors: ([󠀀]，[∠( ᐛ 」∠)＿]，[远志])