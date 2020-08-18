# run-mailcap

> 运行 MailCap 程序
> 针对 mailcap 文件中的各项（或别名）使用给定的操作处理每个 MIME 类型/文件，运行 mailcap 的 `view`、 `see`、 `edit`、 `compose`、 `print` 等各个动作

- 通过指定操作选项，执行单一操作/程序：

`run-mailcap --action=ACTION [--option[=value]]`

- 简单方式：

`run-mailcap --action=ACTION {{filename}}`

- 显示更多信息：

`run-mailcap  --action=ACTION --debug {{filename}}`

- 忽略任何 “copiousoutput”指令，并转发输出内容到标准输出：

`run-mailcap --action=ACTION --nopager {{filename}}`

- 显示发现没有实际对其执行的命令：

`run-mailcap --action=ACTION --norun {{filename}}`

[#]: contributors: ([硬核老王（📺Linux中国）]，[jim.大团结]，[王兴宇，Linux 中國])