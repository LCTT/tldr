# flatpak

> 构建、安装和运行 flatpak 应用及运行时环境

- 运行一个已下载的应用：

`flatpak run {{name}}`

- 从远程源安装应用程序：

`flatpak install {{remote}} {{name}}`

- 列出所有已安装的应用程序和运行时环境：

`flatpak list`

- 更新所有已安装的应用程序和运行时环境：

`flatpak update`

- 添加远程源：

`flatpak remote-add --if-not-exists {{remote_name}} {{remote_url}}`

- 列出所有配置的远程源：

`flatpak remote-list`

[#]: contributors: ([Datura stramonium L.]，[王兴宇]，[鲁面007])