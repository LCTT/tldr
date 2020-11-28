# git submodule

> 查看、更新和管理子模块
> 主页地址: <https://git-scmcom/docs/git-submodule>

- 安装仓库配置的子模块：

`git submodule update --init --recursive`

- 将指定 git 仓库作为子模块添加进来：

`git submodule add {{repository_url}}`

- 将指定 git 仓库作为子模块添加进指定目录：

`git submodule add {{repository_url}} {{path/to/directory}}`

- 依次拉取子模块的最新更新：

`git submodule foreach git pull`

[#]: contributors: ([李峰])