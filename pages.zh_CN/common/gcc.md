# gcc

> 预处理和编译 C 和 C++ 源代码文件，然后将它们连接和集合起来

- 将多个源代码文件编译为可执行文件：

`gcc {{source1.c}} {{source2.c}} -o {{executable}}`

- 允许警告、调试符号出现在输出中：

`gcc {{source.c}} -Wall -Og -o {{executable}}`

- 包括来自不同路径的库：

`gcc {{source.c}} -o {{executable}} -I{{header_path}} -L{{library_path}} -l{{library_name}}`

- 将源代码编译成汇编程序指令：

`gcc -S {{source.c}}`

- 编译源代码，不链接：

`gcc -c {{source.c}}`

[#]: contributors: ([王兴宇]，[Datura stramonium L.]，[꯭F꯭i꯭n꯭d꯭e꯭r꯭]，[翔之广宇])