# hg push

> 将更改从本地存储库推送到指定目标

- 将更改推送到“默认”远程路径：

`hg push`

- 将更改推送到指定的远程存储库：

`hg push {{path/to/destination_repository}}`

- 如果新分支不存在，则推送新分支（默认情况下禁用）：

`hg push --new-branch`

- 指定要推送的特定修订更改集：

`hg push --rev {{revision}}`

- 指定要推送的特定分支：

`hg push --branch {{branch}}`

- 指定要推送的特定书签：

`hg push --bookmark {{bookmark}}`

[#]: contributors: ([潘潘])