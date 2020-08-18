# git diff

> 显示被跟踪的文件的更改内容
> 主页: <https://git-scmcom/docs/git-diff>

- 显示未暂存的、未提交的更改内容：

`git diff`

- 显示所有未提交的更改（包括已暂存文件）：

`git diff HEAD`

- 仅显示暂存（未提交）文件的更改内容：

`git diff --staged`

- 显示自指定时间点（date/time 时间表达式，例如：“1 week 2 days” 或者 ISO 时间格式）：

`git diff 'HEAD@{3 months|weeks|days|hours|seconds ago}'`

- 仅显示自指定提交开始的更改文件的文件名：

`git diff --name-only {{commit}}`

- 输出自指定提交开始的文件创建、重命名和权限修改的统计信息：

`git diff --summary {{commit}}`

- 生成补丁文件：

`git diff > {{target_file}}.patch`

- 对比单个文件在两个分支或提交间的更改：

`git diff {{branch_1}}..{{branch_2}} [--] {{path/to/file}}`

- 在当前分支和指定分支间对比不同的文件：

`git diff {{branch}}:{{path/to/file2}} {{path/to/file}}`

[#]: contributors: ([王興與]，[李峰])