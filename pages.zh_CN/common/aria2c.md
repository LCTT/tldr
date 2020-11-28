# aria2c

> 快速下载程序
> 支持 HTTP（S）、FTP、SFTP、BitTorrent 和 Metalink 

- 将 URI 下载到文件：

`aria2c {{url}}`

- 从多个源下载：

`aria2c {{url_1}} {{url_2}}`

- 下载文件中列出的 URI ：

`aria2c -i {{filename}}`

- 使用多个连接下载（译者注：该参数值介于１～５之间）：

`aria2c -s {{connections_num}} {{url}}`

- 使用用户名和密码从 ftp 下载：

`aria2c --ftp-user={{username}} --ftp-passwd={{password}} {{url}}`

- 限制下载速度（字节／秒）：

`aria2c --max-download-limit={{speed}} {{url}}`

[#]: contributors: ([玉叶]，[王兴宇，Linux & BC]，[Datura stramonium L.])