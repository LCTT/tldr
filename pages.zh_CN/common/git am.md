# git am

> 应用补丁文件通过电子邮件接收提交时很有用
> 可参考命令 `git format-patch` ，该命令用来生成补丁文件
> 主页地址: <https://git-scmcom/docs/git-am>

- 应用补丁文件：

`git am {{path/to/file.patch}}`

- 放弃应用补丁的操作：

`git am --abort`

- 先应用补丁里没有冲突的文件，将冲突块存入 reject 文件：

`git am --reject {{path/to/file.patch}}`

[#]: contributors: ([李峰])