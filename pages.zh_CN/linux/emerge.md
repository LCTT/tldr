# emerge

> Gentoo Linux 包管理工具

- 同步所有包：

`emerge --sync`

- 升级所有包，包括依赖：

`emerge -uDNav @world`

- 跳过更新失败的包，继续上次失败的更新任务：

`emerge --resume --skipfirst`

- 安装新软件包，需确认：

`emerge -av {{package_name}}`

- 移除软件包，需确认：

`emerge -Cav {{package_name}}`

- 移除只作为依赖而安装的孤立软件包：

`emerge -avc`

- 按关键字搜索软件包数据库：

`emerge -S {{keyword}}`

[#]: contributors: ([王兴宇，Linux 中國]，[Sellente_Wang])