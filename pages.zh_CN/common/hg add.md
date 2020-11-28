# hg add

> 将指定文件添加到临时区域以进行 Mercurial 中的下一次提交

- 将文件或目录添加到临时区域：

`hg add {{path/to/file}}`

- 添加与指定模式匹配的所有未暂存文件：

`hg add --include {{pattern}}`

- 添加所有未暂存的文件，不包括与指定模式匹配的文件：

`hg add --exclude {{pattern}}`

- 递归添加子存储库：

`hg add --subrepos`

- 执行测试运行而不执行任何操作：

`hg add --dry-run`

[#]: contributors: ([潘潘])