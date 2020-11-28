# dbus-daemon

> D-Bus 消息守护进程，允许多个进程交换消息

- 运行守护进程时使用一个配置文件：

`dbus-daemon --config-file {{path/to/file}}`

- 使用标准的每个登录对话消息总线配置来运行守护进程：

`dbus-daemon --session`

- 使用标准的系统级消息总线配置来运行守护进程：

`dbus-daemon --system`

- 设置守护进程的监听地址，并覆盖配置的值：

`dbus-daemon --address {{address}}`

- 输出进程号到标准输出：

`dbus-daemon --print-pid`

- 强制消息总线将消息日志写入系统日志：

`dbus-daemon --syslog`

[#]: contributors: ([Jack])