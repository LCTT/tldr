# gocryptfs

> 用 Go 编写的加密覆盖文件系统

- 初始化加密的文件系统：

`gocryptfs -init {{path/to/cipher_dir}}`

- 挂载加密文件系统：

`gocryptfs {{path/to/cipher_dir}} {{path/to/mount_point}}`

- 使用显式主密钥而不是密码进行安装：

`gocryptfs --masterkey {{path/to/cipher_dir}} {{path/to/mount_point}}`

- 更改密码：

`gocryptfs --passwd {{path/to/cipher_dir}}`

- 制作普通目录的加密快照：

`gocryptfs --reverse {{path/to/plain_dir}} {{path/to/cipher_dir}}`

[#]: contributors: ([潘潘])