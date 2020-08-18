# pacman

> 面向 Arch Linux 的包管理器

- 同步并更新所有包：

`pacman -Syu`

- 安装新的软件包：

`pacman -S {{package_name}}`

- 移除一个包以及其依赖：

`pacman -Rs {{package_name}}`

- 使用一个正则表达式或关键词在软件包数据库中进行搜索：

`pacman -Ss "{{search_pattern}}"`

- 列出已安装的包以及其版本：

`pacman -Q`

- 仅列出显式安装的包及其版本：

`pacman -Qe`

- 通过文件名查找某一特定文件所属的包：

`pacman -Qo {{filename}}`

- 清空软件包缓存以清理存储空间：

`pacman -Scc`

[#]: contributors: ([王兴宇，Linux & BC]，[籥]，[Frederick]，[🔆🔆🔆Christopher Lee]，[ZDY])