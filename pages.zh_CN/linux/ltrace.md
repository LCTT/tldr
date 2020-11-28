# ltrace

> 显示进程的动态链接库调用

- 打印（跟踪）程序二进制的库调用：

`ltrace ./{{program}}`

- 对库调用计数在底部打印一个方便的摘要：

`ltrace -c {{/path/to/program}}`

- 跟踪调用 malloc 和 free  ,省略那些由 omit 完成的：

`ltrace -e malloc+free-@libc.so* {{/path/to/program}}`

- 写入文件而不是终端：

`ltrace -o {{file}} {{/path/to/program}}`

[#]: contributors: ([Datura stramonium L.]，[封王浆])