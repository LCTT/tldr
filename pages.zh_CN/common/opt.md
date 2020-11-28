# opt

> 取得 LLVM 源文件并运行指定的优化和（或）分析它们

- 对 bitcode 文件运行优化或分析：

`opt -{{passname}} {{path/to/file.bc}} -S -o {{file_opt.bc}}`

- 将函数的控制流图输出到 “dot” 文件：

`opt {{-dot-cfg}} -S {{path/to/file.bc}} -disable-output`

- 2级优化程序，并将结果输出到另一个文件：

`opt -O2 {{path/to/file.bc}} -S -o {{path/to/output_file.bc}}`

[#]: contributors: ([jim.大团结])