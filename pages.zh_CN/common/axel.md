# axel

> 下载加速器
> 支持 HTTP、HTTPS 和 FTP 协议

- 将指定网址下载保存为文件：

`axel {{url}}`

- 对下载文件指定文件名：

`axel {{url}} -o {{filename}}`

- 多连接下载：

`axel -n {{connections_num}} {{url}}`

- 查询镜像：

`axel -S {{mirrors_num}} {{url}}`

- 限制下载速度（字节/秒）：

`axel -s {{speed}} {{url}}`

[#]: contributors: ([李峰])