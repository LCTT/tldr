# autossh

> 运行、监视和重启 SSH 连接
> 会自动重连，以保持端口传输通道的正常运转可以接受所有的 ssh 标记

- 打开一个 SSH 会话，当监视的端口没有返回数据时重启该会话：

`autossh -M {{monitor_port}} {{ssh_command}}`

- 打开一个将本地端口转发给远程端口的 SSH 会话，必要时重启：

`autossh -M {{monitor_port}} -L {{local_port}}:localhost:{{remote_port}} {{user}}@{{host}}`

- 在执行 ssh 命令之前先 fork 子进程（即运行在后台），并且不打开远程 shell：

`autossh -f -M {{monitor_port}} -N {{ssh_command}}`

- 在后台运行 autossh，不监视端口，而是依赖于 SSH 的保持连接特性，每 10 秒钟检测是否出现连接失败：

`autossh -f -M 0 -N -o "ServerAliveInterval 10" -o "ServerAliveCountMax 3"  {{ssh_command}}`

- 在后台运行不监视端口、不打开远程 shell 的 autossh，如果端口转发失败则退出：

`autossh -f -M 0 -N -o "ServerAliveInterval 10" -o "ServerAliveCountMax 3" -o ExitOnForwardFailure=yes -L {{local_port}}:localhost:{{remote_port}} {{user}}@{{host}}`

- 在后台运行 autossh，并将调试输出记录到文件中，而将冗余输出记录到第二个文件中：

`AUTOSSH_DEBUG=1 AUTOSSH_LOGFILE={{log_file}} autossh -f -M {{monitor_port}} -v -E {{ssh_log_file}} {{ssh_command}}`

[#]: contributors: ([琳小梁]，[王兴宇，Linux 中國]，[张益兴])