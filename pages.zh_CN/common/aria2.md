# aria2

> 一个轻量级的多协议和多源命令行下载实用程序
> 支持 HTTP, HTTPS, FTP, SFTP, BitTorrent 和 Metalink
> 主页:< https://aria2githubio/ >

- 下载网页资源：

`aria2c {{http://example.org/myLinux.iso}}`

- 从多个源下载资源：

`aria2c {{http://mirror1.org/myLinux.iso}} {{http://mirror2.org/myLinux.iso}}`

- 每个主机使用 2 个连接进行下载：

`aria2c -x{{2}} {{http://example.org/myLinux.iso}}`

- 从 Metalink URI 下载：

`aria2c {{http://example.org/myLinux.metalink}}`

- 从 BitTorrent URI 下载：

`aria2c {{http://example.org/myLinux.torrent}}`

- 从 BitTorrent 磁力链接 URI 下载：

`aria2c {{'magnet:?xt=urn:btih:248D0A1CD08284299DE78D5C1ED359BB46717D8C'}}`

- 从文件中下载 URI：

`aria2c -i {{uris.txt}}`

[#]: contributors: ([琳小梁]，[仁人])