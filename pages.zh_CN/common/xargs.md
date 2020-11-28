# xargs

> 使用来自其他命令、文件的管道参数执行命令
> 输入被当做单一的文本块并根据空格、制表符、换行符等分割为单独的参数

- 主要的使用模式：

`{{arguments_source}} | xargs {{command}}`

- 删除拓展名为 `.backup`  的文件 `-print0` 选项表示使用 null 字符来分隔文件， `-0` 选项表示文件分割符为 null （文件名内有空格时使用）：

`find . -name {{'*.backup'}} -print0 | xargs -0 rm -v`

- 对每个输入行执行一次命令，用输入行替换任何出现的占位符（此处标记为`_`）：

`{{arguments_source}} | xargs -I _ {{command}} _ {{optional_extra_arguments}}`

- 并行使用 `max-procs` 个进程，默认是  1如果 `max-procs` 是 0, xargs 会使用尽可能多的进程：

`{{arguments_source}} | xargs -P {{max-procs}} {{command}}`

[#]: contributors: ([zhi]，[李峰]，[王兴宇]，[诗翔])