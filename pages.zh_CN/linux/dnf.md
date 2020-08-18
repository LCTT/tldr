# dnf

> 面向基于红帽系操作系统（RHEL、Fedora、CentOS）的包管理系统（yum 的替代品）

- 安装一个新的软件包：

`sudo dnf install {{package}}`

- 安装一个新的软件包并且假设对所有问题都回答“是”：

`sudo dnf -y install {{package}}`

- 移除一个软件：

`sudo dnf remove {{package}}
`

- 升级一个已安装的包到最新的版本：

`sudo dnf upgrade`

[#]: contributors: ([Frederick]，[白宦成]，[DEx])