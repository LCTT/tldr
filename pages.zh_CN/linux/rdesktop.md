# rdesktop

> 远程桌面协议客户端
> 可以使用RDP协议连接到远程计算机

- 连接到一个月的计算机，默认端口是3389：

`rdesktop -u {{username}} -p {{password}} {{host:port}}`

- 一个简单的示例：

`rdesktop -u Administrator -p passwd123 192.168.1.111:3389`

- -f选项用于启动全屏显示，通过 `Ctrl + Alt + Enter`组合按键退出全屏：

`rdesktop -u {{username}} -p {{password}} -f {{host:port}}`

- 使用自定义的分辨率，注意在两个数字之间使用字母x进行分隔：

`rdesktop -u {{username}} -p {{password}} -g 1366x768 {{host:port}}`

- 使用域名用户连接远程计算机：

`rdesktop -u {{username}} -p {{password}} -d {{domainname}} {{host:port}}`

- 使用16比特颜色，速度更快：

`rdesktop -u {{username}} -p {{password}} -a 16 {{host:port}}`

[#]: contributors: ([无间狂刀]，[Datura stramonium L.])