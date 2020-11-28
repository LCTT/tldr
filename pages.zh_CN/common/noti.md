# noti

> 监视进程并触发横幅通知

- tar完成文件打包后发送一条通知：

`noti {{tar -cjf example.tar.bz2 example/}}`

- 你也可以把它放在要监控的命令后发送通知：

`{{command_to_watch}}; noti`

- 通过PID监控进程，在PID消失后触发一条通知：

`noti -w {{process_id}}`

[#]: contributors: ([darksuོn]，[Judie])