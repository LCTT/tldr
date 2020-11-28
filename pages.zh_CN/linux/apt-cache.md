# apt-cache

> Debian 和 Ubuntu 的软件包查询工具

- 通过当前软件源查询软件包：

`apt-cache search {{query}}`

- 显示软件包的信息：

`apt-cache show {{package}}`

- 显示软件包是否已安装或是否已更新：

`apt-cache policy {{package}}`

- 显示软件包的依赖关系：

`apt-cache depends {{package}}`

- 显示依赖于指定软件包的包文件：

`apt-cache rdepends {{package}}`

[#]: contributors: ([李峰])