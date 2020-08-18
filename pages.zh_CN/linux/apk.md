# apk

> Alpine Linux 的包管理工具

- 从所有登记的远程软件仓库更新本地仓库的软件包索引：

`apk update`

- 安装一个新的软件包：

`apk add {{package}}`

- 移除软件包：

`apk del {{package}}`

- 在不更新依赖的软件包的前提下修复或升级一个软件包：

`apk fix {{package}}`

- 通过关键字搜索软件包：

`apk search {{keyword}}`

- 获取特定软件包的信息：

`apk info {{package}}`

[#]: contributors: ([ZH]，[李桥])