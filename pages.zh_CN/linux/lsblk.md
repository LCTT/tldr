# lsblk

> 列出设备信息

- 以树状格式列出所有存储设备：

`lsblk`

- 同时也显示空设备相关的信息：

`lsblk -a`

- 在大小一列中使用 bytes 来作为单位，而不是使用对人类更友好的格式来显示：

`lsblk -b`

- 输出文件系统相关的信息：

`lsblk -f`

- 在输出树状格式时只使用 ASCII 字符：

`lsblk -i`

- 输出块设备之间的拓扑关系：

`lsblk -t`

[#]: contributors: ([lc]，[Alien]，[darksuོn])