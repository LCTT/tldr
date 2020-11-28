# supervisorctl

> Supervisor 是基于 C/S 架构的可以在使用户在类 UNIX 系统上批量管理命令进程
> Supervisorctl 是 supervisor的命令行客户端，提供类shell的命令交互

- 开始/停止/重启一个子进程process-name 是在supervisor配置文件中定义的，可定义多个：

`supervisorctl {{start|stop|restart}} {{process_name}}`

- 开始/停止/重启一个群组内的所有子进程group-name 是在supervisor配置文件中定义的，可以包括若干个子进程即process-name(即配置文件中的program)：

`supervisorctl {{start|stop|restart}} {{group_name}}:*`

- 显示子进程最后100B的错误日志：

`supervisorctl tail -100 {{process_name}} stderr`

- 持续输出显示子进程的日志：

`supervisorctl tail -f {{process_name}} stdout`

- 重载子进程配置文件如果配置文件添加或减少了子进程项目，需重载后方能实现增减：

`supervisorctl update`

[#]: contributors: ([卜楞儿]，[执殿遮那])