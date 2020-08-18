# bash

> Bourne-Again SHell
> 与 `sh` 兼容的命令解释器

- 开始一个交互性的 Shell：

`bash`

- 执行指定命令：

`bash -c "{{command}}"`

- 运行指定文件中的命令（注：文件可以包含多个命令，以换行分隔）：

`bash {{file.sh}}`

- 从指定的文件中运行命令，将执行的命令记录并显示到终端（屏幕）：

`bash -x {{file.sh}}`

- 从指定的文件中运行命令，在遇到第一个错误时停止执行：

`bash -e {{file.sh}}`

- 运行来源于标准输入（STDIN）的命令：

`bash -s`

- 输出bash的版本信息（使用 `echo $BASH_VERSION` 命令仅显示版本字符串）：

`bash --version`

[#]: contributors: ([柳旺呀]，[琳小梁]，[　]，[󠀀]，[王兴宇，Linux & BC]，[Datura stramonium L.]，[꯭F꯭i꯭n꯭d꯭e꯭r꯭]，[Frederick])