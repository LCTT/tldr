# clang

> C、C++ 和 Objective-C 源文件编译器可作为 GCC 的替代品

- 将源代码文件编译成可执行的二进制文件：

`clang {{input_source.c}} -o {{output_executable}}`

- 显示所有错误和警告的输出：

`clang {{input_source.c}} -Wall -o {{output_executable}}`

- 包括（ include ）位于与源文件不同路径的库：

`clang {{input_source.c}} -o {{output_executable}} -I{{header_path}} -L{{library_path}} -l{{library_name}}`

- 将源代码编译成 LLVM 中介码（译者注：IR 即中间语言）：

`clang -S -emit-llvm {{file.c}} -o {{file.ll}}`

[#]: contributors: ([琳小梁]，[Datura stramonium L.])