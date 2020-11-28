# nslookup

> 查询 DNS 记录

- 在系统默认的dns服务器上查询该域名对应的IP地址(A记录)：

`nslookup {{example.com}}`

- 到指定dns服务器(这里是8.8.8.8)查询该域名对应的NS(名字服务器)记录：

`nslookup -type=NS {{example.com}} {{8.8.8.8}}`

- 反向解析IP地址对应的域名：

`nslookup -type=PTR {{54.240.162.118}}`

- 使用TCP协议查询任何可用记录：

`nslookup -vc -type=ANY {{example.com}} `

- 使用tcp协议向给定名称服务器查询域的整个区域文件(区域传输)：

`nslookup -vc -type=AXFR {{example.com}} {{name_server}}`

- 查询域的邮件服务器(MX记录)，显示事务的详细信息：

`nslookup -type=MX -debug {{example.com}}`

- 查询特定端口号上的给定名称服务器，获取域的TXT记录：

`nslookup -port={{port_number}} -type=TXT {{example.com}} {{name_server}}`

[#]: contributors: ([jim.大团结]，[ㅤ]，[jrg])