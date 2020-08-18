# sftp

> 安全文件传输程序
> 在主机间通过 SSH 复制文件的交互式程序
> 对于非交互式的文件传输，参见 `scp` 或 `rsync`

- 连接至远程服务器并进入一个交互式的命令行界面：

`sftp {{remote_user}}@{{remote_host}}`

- 指定另一个端口进行连接：

`sftp -P {{remote_port}} {{remote_user}}@{{remote_host}}`

- （在交互式界面中）将远程文件下载至本地：

`get {{/path/remote_file}}`

- （在交互式界面中）上传本地文件至远程系统：

`put {{/path/local_file}}`

- （在交互式界面中）递归地下载远程目录到本地（`put` 也可使用该参数）：

`get -R {{/path/remote_directory}}`

- （在交互式界面中）列出本地文件：

`lls`

- （在交互式界面中）列出远程文件：

`ls`

[#]: contributors: ([王興與·區塊鏈·Linux中國]，[蔚然])