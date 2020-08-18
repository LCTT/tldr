# httping

> 测量 http web 服务器的延时与吞吐量

- ping 一个给定的 url ：

`httping -g {{url}}`

- ping web 服务器 ，使用指定的主机名：`host` 与端口： `port`：

`httping -h {{host}} -p {{port}}`

- Ping web 服务器，指定主机名 `host` ，通过使用ssl连接：

`httping -l -g https://{{host}}`

- Ping web服务器，指定主机名： `host` ，使用http基础认证，-U：带用户名，-P：带密码：

`httping -g http://{{host}} -U {{username}} -P {{password}}`

[#]: contributors: ([jim.大团结]，[黄哲])