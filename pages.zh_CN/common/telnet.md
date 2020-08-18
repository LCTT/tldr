# telnet

> 使用telnet协议连接到主机的指定端口

- 使用telnet连接主机的默认端口：

`telnet {{host}}`

- 使用telnet连接到主机的指定端口：

`telnet {{ip_address}} {{port}}`

- 退出一个telnet会话：

`quit`

- 发出默认转义字符组合以终止会话：

`Ctrl + ]`

- 示例：使用x作为会话终止字符启动telnet连接：

`telnet -e {{x}} {{ip_address}} {{port}}`

[#]: contributors: ([乔斌])