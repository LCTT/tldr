# conda

> 任何编程语言的包、依赖和环境管理

- 创建新的环境，并在其中安装指定的包：

`conda create --name {{environment_name}} {{python=2.7 matplotlib}}`

- 列出所有的环境：

`conda info --envs`

- 启用或禁用环境：

`source {{activate|deactivate}} {{environment_name}}`

- 删除环境（移除所有包）：

`conda remove --name {{environment_name}} --all`

- 在 conda 频道中通过名称搜索包：

`conda search {{package_name}}`

- 在当前环境中安装包：

`conda install {{python=3.4 numpy}}`

- 列出当前环境中安装的包：

`conda list`

- 删除未使用的包和缓存：

`conda clean --all`

[#]: contributors: ([CNife]，[jim.大团结])