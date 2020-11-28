# git shortlog

> 简化的 `git log`
> 主页：<https://git-scmcom/docs/git-shortlog>

- 显示所有提交，按提交者姓名分组：

`git shortlog`

- 显示所有提交，按提交数排序：

`git shortlog -n`

- 显示所有提交，按提交者姓名和邮箱地址分组：

`git shortlog -c`

- 查看最近 5 次提交的摘要（即指定修订范围）：

`git shortlog HEAD~{{5}}..HEAD`

[#]: contributors: ([潘潘]，[CNife])