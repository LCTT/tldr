# mosh

> mobile shell（`mosh`）是一个强大且响应迅速的 ssh 替代品
> mosh 在网络间漫游时保持与远程服务器的连接

- 连接到远程服务器：

`mosh {{username}}@{{remote_host}}`

- 使用特定标识（私钥）连接到远程服务器：

`mosh --ssh="ssh -i {{/path/to/key_file}}" {{username}}@{{remote_host}}`

- 连接到远程服务器的特定端口：

`mosh --ssh="ssh -p {{2222}}" {{username}}@{{remote_host}}`

- 在远程服务器上运行命令：

`mosh {{remote_host}} -- {{command -with -flags}}`

- 选择 mosh udp 端口（当远程主机位于 NAT 时很有用）：

`mosh -p {{124}} {{username}}@{{remote_host}}`

- 当 mosh-server 二进制文件不在标准路径时的用法（译者注：/path/to/bin 为 mosh-server 二进制文件的路径）：

`mosh --server={{/path/to/bin/}}mosh-server {{remote_host}}`

[#]: contributors: ([Datura stramonium L.])