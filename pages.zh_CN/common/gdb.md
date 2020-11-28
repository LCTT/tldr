# gdb

> GNU 调试器

- 调试一个可执行文件：

`gdb {{executable}}`

- 将一个进程附着到 gdb：

`gdb -p {{procID}}`

- 一旦启动就执行给定的 gdb 命令：

`gdb -ex "{{commands}}" {{executable}}`

- 启动 gdb 并传递参数：

`gdb --args {{executable}} {{argument1}} {{argument2}}`

[#]: contributors: ([王兴宇]，[jim.大团结])