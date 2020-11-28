# srm

> 安全删除文件及目录
> rm命令的替代品，通过覆盖一次或多次来安全删除数据

- 使用随机数覆盖一次要删除的文件：

`srm -s {{/path/to/file}}`

- 使用随机数覆盖七次要删除的文件：

`srm -m {{/path/to/file}}`

- 使用随机数覆盖一次要删除的文件夹及其内容：

`srm -r -s {{/path/to/directory}}`

- 在每次删除操作之前都提示用户确认：

`srm -i {{\*}}`

[#]: contributors: ([Thomas Lewis])