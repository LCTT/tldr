# nim

> Nim 编译器
> 处理、编译、链接 Nim 语言源文件

- 编译源文件：

`nim compile {{file.nim}}`

- 编译并且运行一个源文件：

`nim compile -r {{file.nim}}`

- 编译启用了发布优化的源文件：

`nim compile -d:release {{file.nim}}`

- 构建针对低文件大小优化的发布二进制文件：

`nim compile -d:release --opt:size {{file.nim}}`

- 为模块生成 HTML 文档（输出将放在当前目录中）：

`nim doc {{file.nim}}`

[#]: contributors: ([潘潘]，[6 °分离])