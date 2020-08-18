# git branch

> git 操作分支的主要命令
> 主页地址: <https://git-scmcom/docs/git-branch>

- 列举出当前本地的分支，当前分支是加亮的：

`git branch`

- 列出所有分支（本地和远程的）：

`git branch -a`

- 在当前提交上建立新分支：

`git branch {{branch_name}}`

- 在一指定提交上建立新分支：

`git branch {{branch_name}} {{commit_hash}}`

- 重命名分支（操作须谨慎）：

`git branch -m {{old_branch_name}} {{new_branch_name}}`

- 删除指定的本地分支（操作须谨慎）：

`git branch -d {{branch_name}}`

[#]: contributors: ([李峰]，[盛曦 姜]，[武杰])