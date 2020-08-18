# git cherry-pick

> 在当前分支应用指定提交的更改
> 想在其他分支上应用修改的话，先用 git-checkout 切换到目的分支
> 主页地址: <https://git-scmcom/docs/git-cherry-pick>

- 在当前分支应用指定提交：

`git cherry-pick {{commit}}`

- 在当前分支应用指定系列提交（参考命令： `git rebase --onto`）：

`git cherry-pick {{start_commit}}~..{{end_commit}}`

- 在当前分支应用多个（不连续的）提交：

`git cherry-pick {{commit_1}} {{commit_2}}`

[#]: contributors: ([李峰])