# ssh-copy-id

> 将你的公钥安装到远程计算机的 `authorized_keys` 中

- 拷贝你的密钥到远程机器：

`ssh-copy-id {{username@remote_host}}`

- 拷贝指定公钥到远程机器：

`ssh-copy-id -i {{path/to/certificate}} {{username}}@{{remote_host}}`

- 拷贝指定公钥到特定端口的远程机器：

`ssh-copy-id -i {{path/to/certificate}} -p {{port}} {{username}}@{{remote_host}}`

[#]: contributors: ([王兴宇，Linux & BC]，[庄秋彬]，[Judie])