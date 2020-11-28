# fastboot

> 与处于引导模式的安卓设备建立连接(一个`adb`命令不起作用的地方)

- 解锁引导模式：

`fastboot oem unlock`

- 上锁引导模式：

`fastboot oem lock`

- 再次将设备从快速启动模式重新启动到快速启动模式：

`fastboot reboot bootloader`

- 刷写给定镜像：

`fastboot flash {{file.zip}}`

- 刷写自定义的 recovery 映像：

`fastboot flash recovery {{file.img}}`

- 显示连接的设备：

`fastboot devices`

[#]: contributors: ([Datura stramonium L.]，[CuiKaihui])