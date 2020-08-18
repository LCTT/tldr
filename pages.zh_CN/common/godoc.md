# godoc

> 显示 go 包的文档

- 显示 "fmt" 包的帮助：

`godoc {{fmt}}`

- 显示 "fmt" 包的 "Printf" 函数的帮助：

`godoc {{fmt}} {{Printf}}`

- 在网页服务器的"6060"端口上提供文档服务：

`godoc -http=:{{6060}}`

- 创建一个索引文件：

`godoc -write_index -index_files={{path/to/file}}`

- 使用给定索引文件搜索文档：

`godoc -http=:{{6060}} -index -index_files={{path/to/file}}`

[#]: contributors: ([jim.大团结])