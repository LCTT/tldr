# dirname

> 计算给定文件或目录路径的父目录

- 计算给定路径的父目录：

`dirname {{path/to/file_or_directory}}`

- 计算多个路径的父目录：

`dirname {{path/to/file_a}} {{path/to/directory_b}}`

- 用 NUL 字符而不是换行符分隔输出（与 `xargs` 组合时很有用）：

`dirname --zero {{path/to/directory_a}} {{path/to/file_b}}`

[#]: contributors: ([琳小梁]，[Datura stramonium L.])