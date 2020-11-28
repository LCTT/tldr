# loc

> 用 Rust 编写的工具，用于计算代码行数

- 在当前目录中打印代码行：

`loc`

- 在目标目录中打印代码行：

`loc {{path/to/directory}}`

- 打印包含各个文件的统计信息的代码行：

`loc --files`

- 打印没有 .gitignore（等）文件的代码行（例如，两个 -u 标志将另外计算隐藏文件和 dirs ）：

`loc -u`

[#]: contributors: ([潘潘])