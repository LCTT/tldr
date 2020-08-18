# hg pull

> 将更改从指定的存储库拉到本地存储库

- 从“默认”源路径拉出：

`hg pull`

- 从指定的源存储库中提取：

`hg pull {{path/to/source_repository}}`

- 将本地存储库更新到远程的头部：

`hg pull --update`

- 即使远程存储库不相关，也要进行更改：

`hg pull --force`

- 指定要提取的特定修订更改集：

`hg pull --rev {{revision}}`

- 指定要拉的特定分支：

`hg pull --branch {{branch}}`

- 指定要拉取的特定书签：

`hg pull --bookmark {{bookmark}}`

[#]: contributors: ([潘潘])