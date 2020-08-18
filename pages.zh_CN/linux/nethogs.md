# nethogs

> 显示每个进程的带宽使用情况

- 以root身份启动nethogs (默认监听的是eth0设备)：

`sudo nethogs`

- 监听指定设备的带宽使用情况：

`sudo nethogs {{device}}`

- 监听多个指定的设备的带宽使用情况：

`sudo nethogs {{device1}} {{device2}}`

- 具体的刷新速率(两次刷新的时间间隔)：

`sudo nethogs -t {{seconds}}`

[#]: contributors: ([梦还在继续])