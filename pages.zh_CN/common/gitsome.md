# gitsome

> 基于终端界面的 GitHub ，可以通过 "gh" 命令进入交互
> 可自动补全 git 命令
> 项目主页: <https://githubcom/donnemartin/gitsome>

- 输入 gitsome shell（可选），为 git（和 gh ）命令启用自动完成和交互式帮助：

`gitsome`

- 设置 GitHub 与当前帐户的集成：

`gh configure`

- 列出当前帐户的通知（如 https://github.com/notifications 中所示）：

`gh notifications`

- 列出当前帐户的已加星标的库，按给定的搜索字符串进行过滤：

`gh starred "{{python 3}}"`

- 查看给定 GitHub 存储库的最近活动源：

`gh feed {{tldr-pages/tldr}}`

- 使用默认页面查看给定 GitHub 用户的最近活动供稿（例如 less ）：

`gh feed {{torvalds}} -p`

[#]: contributors: ([潘潘]，[Mr. Ren])