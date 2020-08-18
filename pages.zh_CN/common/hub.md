# hub

> Git的包装器，用于添加用于处理基于GitHub的项目的命令
> 这些命令也可以使用“git”而不是“hub”

- 使用存储库名称而不是完整 URL 来克隆你拥有的存储库：

`hub clone {{repo_name}}`

- 使用他们的 github 用户名和存储库名称克隆另一个用户的存储库：

`hub clone {{username}}/{{repo_name}}`

- 在 github 配置文件下创建当前存储库的分支（从其他用户克隆）：

`hub fork`

- 将当前本地分支推送到 github 并在原始存储库中为其创建 PR：

`hub push {{remote_name}} && hub pull-request`

- 创建当前（已推送）分支的 PR ，重用第一次提交的消息：

`hub pull-request --no-edit`

- 将当前（仅限本地）存储库上载到你的 github 帐户：

`hub create`

[#]: contributors: ([潘潘]，[Judie])