# rvm

> 一个用于方便安装、管理和使用多个 ruby 环境的工具

- 安装多个版本的 ruby （用一个或多个空间分隔）：

`rvm install {{version(s)}}`

- 显示已安装版本的列表：

`rvm list`

- 使用指定版本的 Ruby：

`rvm use {{version}}`

- 设置默认的 Ruby：

`rvm --default use {{version}}`

- 将指定版本的 Ruby 升级到新版本：

`rvm upgrade {{current_version}} {{new_version}}`

- 卸载指定版本的 Ruby 并保留其源代码：

`rvm uninstall {{version}}`

- 删除指定版本的 Ruby 及其源代码：

`rvm remove {{version}}`

[#]: contributors: ([Datura stramonium L.])