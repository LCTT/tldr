# realpath

> 显示文件或目录的解析绝对路径

- 用于显示文件或目录的绝对路径：

`realpath {{path/to/file_or_directory}}`

- 要求存在所有路径组件：

`realpath --canonicalize-existing {{path/to/file_or_directory}}`

- 在符号链接之前解决“..”组件：

`realpath --logical {{path/to/file_or_directory}}`

- 禁用符号链接扩展：

`realpath --no-symlinks {{path/to/file_or_directory}}`

- 禁止显示错误消息：

`realpath --quiet {{path/to/file_or_directory}}`

[#]: contributors: ([Judie]，[银])