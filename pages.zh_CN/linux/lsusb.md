# lsusb

> 显示 USB 总线和已连接的设备信息

- 列出所有可用的 USB 设备：

`lsusb`

- 以树状结构列出 USB 层级关系：

`lsusb -t`

- 以详细模式列出所有 USB 设备的信息：

`lsusb --verbose`

- 列出此 USB 设备的详细信息：

`lsusb -D {{device}}`

- 只列出属于此特定厂商和产品 id 的 USB 设备：

`lsusb -d {{vendor}}:{{product}}`

[#]: contributors: ([王兴宇]，[胖子])