# hg remove

> 从暂存区域中删除指定的文件

- 从暂存区域中删除文件或目录：

`hg remove {{path/to/file}}`

- 删除与指定模式匹配的所有暂存文件：

`hg remove --include {{pattern}}`

- 删除所有暂存的文件，不包括与指定模式匹配的文件：

`hg remove --exclude {{pattern}}`

- 递归删除子存储库：

`hg remove --subrepos`

- 从存储库中删除已物理删除的文件：

`hg remove --after`

[#]: contributors: ([潘潘])