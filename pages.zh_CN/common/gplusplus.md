# gplusplus

> 用于编译C++ 源文件 （即g++）
> 是 GCC 的一部分 (GNU CompilerCollection)（GNU 编译器）

- 将源代码编译为二进制可执行文件：

`g++ {{source.cpp}} -o {{output_executable}}`

- （几乎）显示出全部的错误与警告提示：

`g++ {{source.cpp}} -Wall -o {{output_executable}}`

- 从 (C++98/C++11/C++14/C++17) 中选择一种语言规范来编译：

`g++ {{source.cpp}} -std={{language_standard}} -o {{output_executable}}`

- 用于包含其他不在源文件目录的函数库：

`g++ {{source.cpp}} -o {{output_executable}} -I{{header_path}} -L{{library_path}} -l{{library_name}}`

[#]: contributors: ([张益兴])