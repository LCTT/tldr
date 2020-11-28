# slapt-get

> Linux 发行版 Slackware 的包管理器，类似 apt 
> 软件包源地址需要在 slapt-getrc 文件里配置

- 更新可用软件包和版本清单：

`slapt-get --update`

- 安装一个程序包，或者将它更新为可用的最新版本：

`slapt-get --install {{package_name}}`

- 卸载一个程序包：

`slapt-get --remove {{package_name}}`

- 将已安装的所有程序包更新为最新可用版本：

`slapt-get --upgrade {{package_name}}`

- 根据包名称、磁盘设置或版本来查找感兴趣的包：

`slapt-get --search {{package_name}}`

- 显示某个程序包的信息：

`slapt-get --show {{package_name}}`

[#]: contributors: ([李峰]，[Mr. Ren])