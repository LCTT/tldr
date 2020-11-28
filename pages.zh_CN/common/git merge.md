# git merge

> 合并分支
> 主页地址: <https://git-scmcom/docs/git-merge>

- 指定分支于当前分支合并：

`git merge {{branch_name}}`

- 编辑合并消息：

`git merge -e {{branch_name}}`

- 合并指定分支并生成一条合并提交：

`git merge --no-ff {{branch_name}}`

- 如有文件冲突则放弃合并：

`git merge --abort`

[#]: contributors: ([李峰])