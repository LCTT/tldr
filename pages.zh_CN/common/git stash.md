# git stash

> 将本地 Git 变更储藏到临时区域
> 主页地址: <https://git-scmcom/docs/git-stash>

- 储藏当前变更，新文件（未跟踪文件）除外：

`git stash [save {{optional_stash_message}}]`

- 储藏当前变更，包括新文件（未跟踪文件）：

`git stash -u`

- 交互式储藏部分变更文件：

`git stash -p`

- 列出所有储藏（显示储藏名、相关分支和留言）：

`git stash list`

- 应用储藏（默认为 stash@{0} - 最近一次储藏）：

`git stash apply {{optional_stash_name_or_commit}}`

- 应用储藏（默认为最近的储藏），如无冲突，将其从储藏栈中移除：

`git stash pop {{optional_stash_name}}`

- 丢弃储藏（默认为最近的储藏）：

`git stash drop {{optional_stash_name}}`

- 清空所有的储藏：

`git stash clear`

[#]: contributors: ([李峰])