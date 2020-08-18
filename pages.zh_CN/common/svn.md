# svn

> Subversion 命令行客户端工具

- 从版本仓库中取出一份工作用的拷贝到当前的文件系统：

`svn co {{url/to/repository}}`

- 把版本仓库中的最新修改合入本地副本：

`svn up`

- 将文件和目录纳入版本控制系统，准备把这些文件提交到版本仓库中这些文件会在下次提交时加入版本仓库：

`svn add {{PATH}}`

- 将本地工作副本的修改提交到版本仓库：

`svn ci -m {{commit log message}} [{{PATH}}]`

- 显示最近10次修改及每次修改变更的文件：

`svn log -vl {{10}}`

- 打印详细的帮助文档：

`svn help`

[#]: contributors: ([公孙林]，[李桥])