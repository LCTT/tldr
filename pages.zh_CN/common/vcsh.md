# vcsh

> 使用Git仓库构建的Home目录版本控制系统

- 初始化一个(空的)仓库：

`vcsh init {{repository_name}}`

- 以自定义的目录名称克隆一个仓库：

`vcsh clone {{git_url}} {{repository_name}}`

- 列出所有受管理的仓库：

`vcsh list`

- 在受管理的仓库上执行一个Git命令：

`vcsh {{repository_name}} {{git_command}}`

- 推送/拉取 所有受管理的仓库 到/从 远程目录：

`vcsh {{push|pull}}`

- 为受控制的仓库写入一个自定义.gitignre文件：

`vcsh write-gitignore {{repository_name}}`

[#]: contributors: ([Mr. Ren])