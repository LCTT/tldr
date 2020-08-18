# hostess

> 用于管理 `/etc/hosts` 文件的命令行程序

- 列出域与目标 ip 以及其启用状态（on/off）：

`hostess list`

- 将指向您的计算机的域添加到主机文件（`/etc/hosts`）中：

`hostess add {{local.example.com}} {{127.0.0.1}}`

- 从主机文件中删除域：

`hostess del {{local.example.com}}`

- 禁用域（但不要完全删除）：

`hostess off {{local.example.com}}`

[#]: contributors: ([王兴宇，Linux & BC]，[Datura stramonium L.])