# scp

> 安全复制
> 使用 ssh 上的安全复制协议在主机之间复制文件

- 复制一个本地文件到远程主机：

`scp {{path/to/local_file}} {{remote_host}}:{{path/to/remote_file}}`

- 从远程主机复制一个文件到本地文件夹：

`scp {{remote_host}}:{{path/to/remote_file}} {{path/to/local_dir}}`

- 递归地从一个远程主机复制一个目录的内容到一个本地目录：

`scp -r {{remote_host}}:{{path/to/remote_directory}} {{path/to/local_directory}}`

- 通过本地主机在两个远程主机间复制文件：

`scp -3 {{host1}}:{{path/to/remote_file}} {{host2}}:{{path/to/remote_dir}}`

- 使用指定的用户名连接远程主机：

`scp {{path/to/local_file}} {{remote_username}}@{{remote_host}}:{{path/to/remote_dir}}`

- 使用特定的 ssh 私钥来验证远程主机：

`scp -i {{~/.ssh/private_key}} {{local_file}} {{remote_host}}:{{/path/remote_file}}`

[#]: contributors: ([王兴宇]，[Amor]，[微风徐徐])