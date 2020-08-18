# git-imerge

> 以递增方式在两个 git 分支之间执行合并或重组
> 分支之间的冲突被跟踪到单个提交对，以简化冲突解决
> 主页：<https://githubcom/mhagger/git-imerge>

- 启动基于 imerge 的 rebase（首先检查要重新奠基的分支）：

`git imerge rebase {{branch_to_rebase_onto}}`

- 启动基于 imerge 的合并（首先签出要合并的分支）：

`git imerge merge {{branch_to_be_merged}}`

- 显示正在进行的合并或 rebase 的 ASCII 图：

`git imerge diagram`

- 解决冲突后继续 imerge 操作（首先是 git add 冲突的文件）：

`git imerge continue --no-edit`

- 解决所有冲突后，完成 imerge 操作：

`git imerge finish`

- 中止 imerge 操作，并返回上一个分支：

`git-imerge remove && git checkout {{previous_branch}}`

[#]: contributors: ([潘潘])