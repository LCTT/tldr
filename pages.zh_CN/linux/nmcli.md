# nmcli

> 用于控制 NetworkManager 的命令行工具

- 列出所有的 NetworkManager 连接（包括名字、uuid、类型和设备）：

`nmcli connection`

- 打印可用的 Wi-Fi 接入点：

`nmcli device wifi`

- 用指定的名字和密码连接到 Wi-Fi 网络：

`nmcli device wifi connect {{name}} {{password}}`

- 根据指定的 uuid 启用连接（类似于 `ifup`）：

`nmcli connection up uuid {{uuid}}`

- 根据指定的 uuid 禁用连接（类似于 `ifdown`）：

`nmcli connection down uuid {{uuid}}`

- 显示网卡的状态信息：

`nmcli device status`

[#]: contributors: ([王兴宇，Linux 中國]，[孙达])