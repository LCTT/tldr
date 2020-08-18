# socat

> 多用途中继（SOcket CAT）

- 监听端口，等待传入连接并将数据传输到标准IO （STDIO）：

`socat - TCP-LISTEN:8080,fork`

- 监听 80/TCP 端口：

`socat - TCP4:www.domain.com:80`

- 通过指定端口连接到主机，通过 STDIO 与主机传输数据：

`socat TCP-LISTEN:80,fork TCP4:www.domain.com:80`

[#]: contributors: ([王興與·區塊鏈·Linux中國]，[Datura stramonium L.])