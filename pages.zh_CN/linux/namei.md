# namei

> 列出一个路径中所有的成分，包含符号连接，直到找到那个终端点（文件/目录/字符设备等）
> 本指令对于发现“符号链接层次过多”问题很有帮助

- 解析参数所指定的路径：

`namei {{path/to/a}} {{path/to/b}} {{path/to/c}}`

- 以长列表格式显示结果：

`namei --long {{path/to/a}} {{path/to/b}} {{path/to/c}}`

- 以 `ls` 的形式显示每种文件类型的模式位（例如 'rwxr-xr-x'）：

`namei --modes {{path/to/a}} {{path/to/b}} {{path/to/c}}`

- 显示每个文件的属主和组名：

`namei --owners {{path/to/a}} {{path/to/b}} {{path/to/c}}`

- 执行时不遵循符号链接：

`namei --nosymlinks {{path/to/a}} {{path/to/b}} {{path/to/c}}`

[#]: contributors: ([琳小梁]，[Nonamev]，[money]，[Datura stramonium L.]，[（^_^）]，[王兴宇，Linux 中國])