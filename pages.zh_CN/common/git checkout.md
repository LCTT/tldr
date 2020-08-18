# git checkout

> 切换分支或者恢复工作树
> 主页地址: <https://git-scmcom/docs/git-checkout>

- 创建并且切换到一个新分支：

`git checkout -b {{branch_name}}`

- 创建以及切换到基于一个指定引用的新分支，引用为以下： (branch, remote/branch, tag)等有效的引用：

`git checkout -b {{branch_name}} {{reference}}`

- 切换到一个已经存在的本地分支：

`git checkout {{branch_name}}`

- 切换到一个已经存在的远程分支：

`git checkout --track {{remote_name}}/{{branch_name}}`

- 在当前的文件目录中，丢弃所有未暂存的修改（可以看 `git reset` 获得更多的撤销类似的命令：

`git checkout .`

- 丢弃给定文件中未暂存的改变（恢复暂存区的指定文件到工作区）：

`git checkout {{file_name}}`

- 替换当前目录中的一个文件为指定分支的文件（必须是已经提交的文件）：

`git checkout {{branch_name}} -- {{file_name}}`

[#]: contributors: ([李峰]，[黄哲])