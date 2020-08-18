# guix package

> 安装、升级和删除 Guix 包，或回滚到以前的配置

- 安装一个新包：

`guix package -i {{package_name}}`

- 移除一个包：

`guix package -r {{package_name}}`

- 用正则表达式在包数据库中搜索：

`guix package -s "{{search_pattern}}"`

- 列出已安装的包：

`guix package -I`

- 列出 generations：

`guix package -l`

- 回滚到上一代：

`guix package --roll-back`

[#]: contributors: ([Datura stramonium L.])