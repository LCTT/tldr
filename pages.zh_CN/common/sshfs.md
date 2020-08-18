# sshfs

> 基于 ssh 的文件系统客户端

- 挂载远程目录：

`sshfs {{username}}@{{remote_host}}:{{remote_directory}} {{mountpoint}}`

- 卸载远程目录：

`umount {{mountpoint}}`

- 通过特定端口，挂载服务器远程目录：

`sshfs {{username}}@{{remote_host}}:{{remote_directory}} -p {{2222}}`

- 使用压缩挂载远程目录：

`sshfs {{username}}@{{remote_host}}:{{remote_directory}} -C`

- 挂载远程目录，并追随符号链接：

`sshfs -o follow_symlinks {{username}}@{{remote_host}}:{{remote_directory}} {{mountpoint}}`

[#]: contributors: ([王興與·區塊鏈·Linux中國]，[青榉]，[6 °分离])