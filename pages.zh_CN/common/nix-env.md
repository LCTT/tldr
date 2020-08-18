# nix-env

> 操作或查询 Nix 用户环境

- 显示可用软件包，包括未指定名称的：

`nix-env -qa {{pkg_name}}`

- 显示可用软件状态：

`nix-env -qas`

- 安装指定软件包：

`nix-env -i {{pkg_name}}`

- 卸载指定软件包：

`nix-env -e {{pkg_name}}`

- 更新指定软件包：

`nix-env -u {{pkg_name}}`

- 更新所有软件包：

`nix-env -u`

[#]: contributors: ([李峰])