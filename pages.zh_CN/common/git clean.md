# git clean

> 从工作树中删除未跟踪的文件
> 主页：<https://git-scmcom/docs/git-clean>

- 删除git没有跟踪的文件：

`git clean`

- 交互式地删除git没有跟踪的文件：

`git clean -i`

- 显示哪些文件将被删除，而不是实际删除它们：

`git clean --dry-run`

- 强制删除git没有跟踪的文件：

`git clean -f`

- 强制删除git没有跟踪的目录：

`git clean -fd`

- 删除未跟踪的文件，包括在.gitignore文件和.git/info/exclude忽略的：

`git clean -x`

[#]: contributors: ([潘潘]，[南北桥])