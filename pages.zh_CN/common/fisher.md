# fisher

> Fisher, fish-shell 插件管理器
> 通过名称或使用 'fishfile' 安装插件用于绑定安装

- 安装一个或多个插件：

`fisher {{plugin1}} {{plugin2}}`

- 从 GitHub gist 安装插件：

`fisher {{gist_url}}`

- 用自己喜欢的编辑器手工编辑 'fishfile' 并安装多个插件：

`{{editor}} ~/.config/fish/fishfile; fisher`

- 列出已安装的插件：

`fisher ls`

- 显示可用的插件：

`fisher ls-remote`

- 升级插件：

`fisher up`

- 卸载一个或多个插件：

`fisher rm {{plugin1}} {{plugin2}}`

[#]: contributors: ([jim.大团结])