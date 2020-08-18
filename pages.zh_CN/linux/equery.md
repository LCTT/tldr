# equery

> 显示 Portage 包的信息

- 列出所有已安装的包：

`equery list '*'`

- 在 Portage 树和覆盖中搜索已安装的软件包：

`equery list -po {{package_name}}`

- 列出依赖于给定包的所有包：

`equery depends {{package_name}}`

- 列出给定包依赖的所有包：

`equery depgraph {{package_name}}`

- 列出程序包安装的所有文件：

`equery files --tree {{package_name}}`

[#]: contributors: ([潘潘]，[jim.大团结])