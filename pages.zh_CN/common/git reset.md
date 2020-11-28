# git reset

> 通过重置当前 git HEAD 到指定状态来撤销提交或暂存的变更
> 若参数为文件路径则撤销暂存，若参数为哈希码或分支则撤销提交
> 主页地址: <https://git-scmcom/docs/git-reset>

- 撤销所有暂存：

`git reset`

- 撤销指定文件暂存：

`git reset {{path/to/file(s)}}`

- 撤销文件部分暂存：

`git reset -p {{path/to/file}}`

- 撤销上次提交，变更在文件系统中保留（包括那些未提交的变更）：

`git reset HEAD~`

- 撤销最近两次提交，索引变更，即暂存变更：

`git reset --soft HEAD~2`

- 丢弃所有未提交的（暂存的、未暂存的）变更，用 git checkout 命令仅丢弃未暂存变更：

`git reset --hard`

- 重置仓库到指定提交，丢弃此提交后的所有更改：

`git reset --hard {{commit}}`

[#]: contributors: ([李峰])