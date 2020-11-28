# shopt

> 管理 Bash shell 选项: 指定这些选项（以变量的形式保存于 `$BASHOPTS` 之中）可以控制 Bash shell 的功能
> 多数 POSIX shell 变量 (保存在 `$SHELLOPTS` 之中) 也可以用 `set` 命令进行管理

- 所有可设置选项的列表以及是否已设置：

`shopt`

- 设置选项：

`shopt -s {{option_name}}`

- 取消选项：

`shopt -u {{option_name}}`

- 用 `shopt` 命令可直接运行的格式，输出所有选项及其当前状态：

`shopt -p`

- 显示命令的帮助：

`help shopt`

[#]: contributors: ([毕玮]，[玉叶])