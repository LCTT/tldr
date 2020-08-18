# hg log

> 显示存储库的修订历史记录

- 显示存储库的整个修订历史记录：

`hg log`

- 使用 ASCII 图显示修订历史记录：

`hg log --graph`

- 显示具有与指定模式匹配的文件名的修订历史记录：

`hg log --include {{pattern}}`

- 显示修订历史记录，不包括与指定模式匹配的文件名：

`hg log --exclude {{pattern}}`

- 显示特定修订的日志信息：

`hg log --rev {{revision}}`

- 显示特定分支的修订历史记录：

`hg log --branch {{branch}}`

- 显示特定日期的修订历史记录：

`hg log --date {{date}}`

- 显示特定用户提交的修订：

`hg log --user {{user}}`

[#]: contributors: ([潘潘]，[玉叶])