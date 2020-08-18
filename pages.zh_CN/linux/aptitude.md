# aptitude

> Debian 和 Ubuntu 包管理实用程序

- 同步可用的包和版本列表应该在运行后继的 aptitude 命令前运行：

`aptitude update`

- 安装新包及其依赖项：

`aptitude install {{package}}`

- 搜索包：

`aptitude search {{package}}`

- 移除该包及所有依赖其的包：

`aptitude remove {{package}}`

- 将已安装的包升级到最新的可用版本：

`aptitude upgrade`

- 更新安装的包（类似于 `aptitude upgrade`），包括移除废弃的包和安装更多的包以满足新的包的依赖条件：

`aptitude full-upgrade`

[#]: contributors: ([Namhaid]，[王兴宇，Linux & BC]，[Datura stramonium L.])