# git log

> 显示提交历史
> 主页地址: <https://git-scmcom/docs/git-log>

- 显示提交列表，从最近一次提交开始按时间倒序排列：

`git log`

- 显示直接文件或目录的提交历史，打印差异：

`git log -p {{path/to/file_or_directory}}`

- 只显示每次提交记录的第一行：

`git log --oneline`

- 显示每次提交变更文件总览：

`git log --stat`

- 已图形模式显示当前分支提交历史：

`git log --graph`

- 以图形模式显示整个仓库的所有提交、标签和分支：

`git log --oneline --decorate --all --graph`

- 仅显示提交信息包含指定字符串的提交（大小写敏感）：

`git log -i --grep {{search_string}}`

[#]: contributors: ([李峰])