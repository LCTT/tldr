# dpkg-query

> 显示安装的软件包信息的工具

- 列出全部已安装的包：

`dpkg-query -l`

- 列出满足匹配规则的已安装的软件包：

`dpkg-query -l '{{pattern}}'`

- 列出指定软件包安装的所有文件：

`dpkg-query -L {{package_name}}`

- 显示指定软件包的信息：

`dpkg-query -s {{package_name}}`

[#]: contributors: ([李峰])