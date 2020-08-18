# bw

> 一个用来管理 Bitwarden 保险柜的命令行工具

- 登录 Bitwarden 用户账户：

`bw login`

- 登出 Bitwarden 用户账户：

`bw logout`

- 从 Bitwarden 保险柜中所以搜索并且显示项目：

`bw list items --search {{github}}`

- 显示特定的 Bitwarden 保险柜项目：

`bw get item {{github}}`

- 在 Bitwarden 保险柜中创建一个文件夹：

`{{echo -n '{"name":"My Folder1"}' | base64}} | bw create folder`

[#]: contributors: ([咪咪咪🍼])