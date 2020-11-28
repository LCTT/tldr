# firejail

> 基于 Linux 内置功能的沙箱工具，将进程安全地映射到容器沙箱中

- 将 firejail 整合进你的桌面环境：

`sudo firecfg`

- 打开一个受限的 Firefox 浏览器：

`firejail {{firefox}}`

- 在指定 IP 和网络接口下启动一个受限的 Apache 服务器：

`firejail --net={{eth0}} --ip={{192.168.1.244}} {{/etc/init.d/apache2}} {{start}}`

- 列出正在运行的沙箱：

`firejail --list`

- 列出正在运行中的沙箱的网络活动：

`firejail --netstats`

- 关掉一个正在运行的沙箱：

`firejail --shutdown={{7777}}`

[#]: contributors: ([胖鱼])