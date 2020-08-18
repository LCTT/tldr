# smbclient

> 类FTP客户端，用于访问服务器提供的SMB/CIFS资源

- 连接到一个smb共享服务(用户会被提示输入密码; “exit” 用来退出该进程)：

`smbclient {{//server/share}}`

- 使用指定用户名连接smb服务：

`smbclient {{//server/share}} --user {{username}}`

- 使用指定用户名和密码连接smb服务：

`smbclient {{//server/share}} --user {{username%password}}`

- 从smb服务器下载一个文件：

`smbclient {{//server/share}} --directory {{path/to/directory}} --command "get {{file.txt}}"`

- 上传一个文件到smb服务器：

`smbclient {{//server/share}} --directory {{path/to/directory}} --command "put {{file.txt}}"`

[#]: contributors: ([rabbittony刘晓东-工作时间失联])