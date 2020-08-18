# fswatch

> 跨平台的文件变更监控器

- 观察指定文件创建、更新或删除时执行 bash 命令：

`fswatch {{path/to/file}} | xargs -n 1 {{bash_command}}`

- 观察指定的一个文件、多个文件或目录：

`fswatch {{path/to/file}} {{path/to/directory}} {{path/to/another_directory/**/*.js}} | xargs -n 1 {{bash_command}}`

- 文件变更时打印出其绝对路径：

`fswatch {{path/to/directory}} | xargs -n 1 -I {} echo {}`

- 根据事件类型，如：更新、删除或创建，来进行筛除：

`fswatch --event {{Updated}} {{path/to/directory}} | xargs -n 1 {{bash_command}}`

[#]: contributors: ([李峰])