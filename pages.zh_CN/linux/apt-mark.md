# apt-mark

> 用于更改安装状态的实用程序

- 将包标记为自动安装：

`sudo apt-mark auto {{package_name}}`

- 保持程序包为当前版本并阻止对其进行更新：

`sudo apt-mark hold {{package_name}}`

- 允许再次更新程序包：

`sudo apt-mark unhold {{package_name}}`

- 显示手动安装的程序包：

`apt-mark showmanual`

- 显示未更新的保留包：

`apt-mark showhold`

[#]: contributors: ([Datura stramonium L.])