# apt-get

> Debian 与 Ubuntu 的包管理应用程序
> 搜索软件包可使用 `apt-cache` 命令

- 更新可用软件包的列表和版本（此命令建议在使用其它 `apt-get` 命令前运行）：

`apt-get update`

- 安装一个软件包，或者将其更新至最新的可用版本：

`apt-get install {{package}}`

- 移除一个软件包，但保留配置文件：

`apt-get remove {{package}}`

- 移除一个软件包及其配置文件：

`apt-get purge {{package}}`

- 将所有已安装的软件包更新至最新的可用版本：

`apt-get upgrade`

- 移除所有不再需要的软件包（保留配置文件）：

`apt-get autoremove`

- 更新已安装的软件包（就像 `upgrade` ），移除过时的软件包并安装额外的软件包以满足新的依赖关系：

`apt-get dist-upgrade`

[#]: contributors: ([王兴宇，Linux & BC]，[悠然间])