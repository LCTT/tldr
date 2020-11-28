# apt

> 面向基于 Debian 的发行版系统的包管理应用程序

- 更新可用软件包的列表和版本（此命令建议在使用其它  `apt` 命令前运行）：

`sudo apt update`

- 搜索给定的软件包：

`apt search {{package}}`

- 查询软件包的信息：

`apt show {{package}}`

- 安装软件包，或者将其更新至最新的可用版本：

`sudo apt install {{package}}`

- 移除软件包（使用 `purge` 替代，可移除相应的配置文件）：

`sudo apt remove {{package}}`

- 更新所有软件包至其最新的可用版本：

`sudo apt upgrade`

[#]: contributors: ([琳小梁]，[悠然间])