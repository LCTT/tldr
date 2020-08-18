# lsof

> 列出打开的文件和对应的进程
> 注意：需要有 Root 权限（或者 sudo）才能列出其他人打开的文件

- 找到打开指定文件的进程：

`lsof {{path/to/file}}`

- 找出打开本地因特网端口的进程：

`lsof -i :{{port}}`

- 只列出进程的 ID：

`lsof -t {{path/to/file}}`

- 列出指定用户打开的文件：

`lsof -u {{username}}`

- 列出给定的命令或者进程打开的文件：

`lsof -c {{process_or_command_name}}`

- 列出给定PID的特定进程打开的文件：

`lsof -p {{PID}}`

- 列出目录中被打开的文件：

`lsof +D {{path/to/directory}}`

[#]: contributors: ([Johnny.Li])