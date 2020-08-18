# tokei

> 输出代码统计信息的程序

- 得出在目录及子目录中代码的报告：

`tokei {{path/to/directory}}`

- Get a report for a directory excluding  file
得出目录中不包含 `.min.js` 文件的报告：

`tokei {{path/to/directory}} -e {{*.min.js}}`

- 目录中分文件输出统计信息：

`tokei {{path/to/directory}} --files`

- 得到目录中所有 Rust 和 Markdown 文件的报告：

`tokei {{path/to/directory}} -t={{Rust}},{{Markdown}}`

[#]: contributors: ([jim.大团结])