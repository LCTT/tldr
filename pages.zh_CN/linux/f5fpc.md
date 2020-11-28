# f5fpc

> 一个由 BIG-IP Edge 提供的专用商用 SSL VPN 客户端

- 新建一个VPN连接：

`sudo f5fpc --start`

- 新建一个连接到指定主机的对话：

`sudo f5fpc --start --host {{host.example.com}}`

- 指定一个使用者（使用者将迅速获得一个密码）：

`sudo f5fpc --start --host {{host.example.com}} --username {{user}}`

- 显示当前VPN连接状态：

`sudo f5fpc --info`

- 关闭VPN会话：

`sudo f5fpc --stop`

[#]: contributors: ([Datura stramonium L.]，[Mr. Ren])