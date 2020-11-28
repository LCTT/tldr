# rabin2

> 获取二进制文件（ELF、PE、Java 类、MACH-O）的信息，符号、节、链接库等
> 与 `radare2` 捆绑在一起

- 显示有关二进制文件的常规信息（架构、类型、字节序）：

`rabin2 -I {{path/to/binary}}`

- 显示链接库：

`rabin2 -l {{path/to/binary}}`

- 显示从库导入的符号：

`rabin2 -i {{path/to/binary}}`

- 显示二进制文件中包含的字符串：

`rabin2 -z {{path/to/binary}}`

- 以 JSON 形式输出：

`rabin2 -j -I {{path/to/binary}}`

[#]: contributors: ([Datura stramonium L.])