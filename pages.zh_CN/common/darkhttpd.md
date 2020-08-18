# darkhttpd

> Darkhttpd 网络服务器

- 启动服务器在指定的文档根目录：

`darkhttpd {{path/to/docroot}}`

- 在指定端口上启动服务器（如果以非 root 用户身份运行，则默认为端口 8080）：

`darkhttpd {{path/to/docroot}} --port {{port}}`

- 仅监听指定的 IP 地址（默认情况下，服务器侦听所有接口）：

`darkhttpd {{path/to/docroot}} --addr {{ip_address}}`

[#]: contributors: ([琳小梁]，[潘潘])