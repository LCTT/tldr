# nc

> 读取和写入 tcp 或 udp 数据

- 监听在指定端口：

`nc  -l {{port}}`

- 连接到某个端口（然后可以通过该端口交互）：

`nc {{ip_address}} {{port}}`

- 设置超时时间：

`nc -w {{timeout_in_seconds}} {{ipaddress}} {{port}}`

- 传输文件：

`nc -l {{port}} < {{file}}`

- 接收文件：

`nc {{ip_address}} {{port}} > {{file}}`

- 即使客户端连接断了依然保持监听：

`nc -k -l {{port}}`

- 客户端在 EOF 后停留：

`nc -q {{timeout}} {{ip_address}}`

- 端口扫描：

`nc -v -z {{ip_address}} {{port}}`

- 代理转发：

`nc -l {{port}} | nc {{hostname}} {{port}}`

[#]: contributors: ([jim.大团结]，[李峰]，[Datura stramonium L.]，[Evil Morty])