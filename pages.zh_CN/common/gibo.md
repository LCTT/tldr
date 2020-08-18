# gibo

> 获取 gitignore 样板

- 列出可用的样板：

`gibo list`

- 写一个样板到 stdout ：

`gibo dump {{boilerplate}}`

- 写一个样板文件给 .gitignore ：

`gibo dump {{boilerplate}} >>{{.gitignore}}`

- 搜索包含给定字符串的样板：

`gibo search {{string}}`

- 更新可用的本地 boilerplates ：

`gibo update`

[#]: contributors: ([潘潘])