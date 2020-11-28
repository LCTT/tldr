# git show

> 显示多种 git 对象（如提交、标签等）
> 主页：<https://git-scmcom/docs/git-show>

- 显示最近一次提交的信息（说明、变更和其他数据）：

`git show`

- 显示指定提交的信息：

`git show {{commit}}`

- 显示与指定标签关联的提交：

`git show {{tag}}`

- 显示指定分支第 3 新的提交：

`git show {{branch}}~{{3}}`

- 在一行中显示指定提交的哈希值和说明，不输出 diff：

`git show --oneline -s {{commit}}`

[#]: contributors: ([CNife])