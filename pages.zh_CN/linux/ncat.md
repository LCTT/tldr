# ncat

> 在网络上使用普通的 `cat` 功能

- 侦听指定端口上的输入并将其写入指定的文件：

`ncat -l {{port}} > {{path/to/file}}`

- 接受多个连接，关闭后保持 ncat 打开：

`ncat -lk {{port}}`

- 将指定文件的输出写入指定端口上的指定主机：

`ncat {{address}} {{port}} < {{path/to/file}}`

[#]: contributors: ([Datura stramonium L.])