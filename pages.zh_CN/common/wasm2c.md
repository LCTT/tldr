# wasm2c

> 将文件从 Webassembly 二进制格式转换为 C 源文件和头文件

- 将文件转换为 C 源文件和头文件并将其显示到控制台：

`wasm2c {{file.wasm}}`

- 将输出写入给定文件（额外生成 file.h）：

`wasm2c {{file.wasm}} -o {{file.c}}`

[#]: contributors: ([Datura stramonium L.])