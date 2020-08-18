# pacaur

> 一个通过 Arch 用户软件仓库（AUR）为 Arch Linux 编译和安装包的实用程序

- 同步和更新所有包（包括 AUR ）：

`pacaur -Syu`

- 只同步和更新 AUR 包：

`pacaur -Syua`

- 安装一个包（包括 AUR ）：

`pacaur -S {{package_name}}`

- 卸载一个包以及它的依赖（包括 AUR 包）：

`pacaur -Rs {{package_name}}`

- 在包数据库中搜索关键词（包括 AUR ）：

`pacaur -Ss {{keyword}}`

- 列出当前所有已安装的包（包括 AUR 包）：

`pacaur -Qs`

[#]: contributors: ([青榉])