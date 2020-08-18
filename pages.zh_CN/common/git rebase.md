# git rebase

> 从另一个分支上的一个分支重新应用提交
> 通常用于将整个分支 “移动” 到另一个分支，在新位置创建提交的副本
> 主页：<https://git-scmcom/docs/git-rebase>

- 将当前分支重新基于主分支：

`git rebase {{master}}`

- 启动交互式 rebase ，允许重新排序，省略，组合或修改提交：

`git rebase -i {{target_base_branch_or_commit_hash}}`

- 在编辑冲突的文件后，继续由失败中断的合并：

`git rebase --continue`

- 中止正在进行的 rebase（例如，如果它被合并冲突中断）：

`git rebase --abort`

- 将当前分支的一部分移动到新基础上，从旧基础开始：

`git rebase --onto {{new_base}} {{old_base}}`

- 重新应用最后 5 次提交，停止允许重新排序，省略，组合或修改它们：

`git rebase -i {{HEAD~5}}`

[#]: contributors: ([潘潘])