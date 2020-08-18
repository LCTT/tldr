# git worktree

> 管理连接到同一代码库的多个工作树
> 主页地址: <https://git-scmcom/docs/git-worktree>

- 创建新的目录，将指定分支检出到该目录下：

`git worktree add {{path/to/folder}} {{branch}}`

- 创建新的目录，创建新分支，并检出到新创建的目录下：

`git worktree add {{path/to/folder}} -b {{new_branch}}`

- 列出该仓库下所有的链接工作树：

`git worktree list`

- 清除已删除的工作树：

`git worktree prune`

[#]: contributors: ([李峰])