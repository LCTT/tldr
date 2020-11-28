# help2man

> 从可执行文件的 --help 和 --version 输出生成简单的手册页

- 生成可执行文件的手册页：

`help2man {{executable}}`

- 在手册页中指定“名称”段落：

`help2man {{executable}} --name {{name}}`

- 指定手册页的部分（默认为1）：

`help2man {{executable}} --section {{section}}`

- 输出到文件而不是 stdout ：

`help2man {{executable}} --output {{path/to/file}}`

- 显示详细帮助：

`help2man --help`

[#]: contributors: ([潘潘])