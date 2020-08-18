# killall

> 通过名称（必须是确切的名称）向进程的所有实例发送“终止”信号
> 所有的信号，除了 SIGKILL 和 SIGSTOP 可以被进程拦截，其余的进程都会“清爽地”终止（退出）

- 使用默认的 SIGTERM（终止）信号终止进程：

`killall {{process_name}}`

- 列出可用的信号名称（没有“SIG”前缀的）：

`killall --list`

- 终止前要求确认：

`killall -i {{process_name}}`

- 使用 SIGINT （中断）信号终止一个进程，该信号和按下 `Ctrl + C` 发送的信号相同：

`killall -INT {{process_name}}`

- 强制结束一个进程：

`killall -KILL {{process_name}}`

[#]: contributors: ([王兴宇，Linux 中國]，[张益兴])