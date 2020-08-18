# pkill

> 按名字给进程发送信号
> 大多用于终止进程

- 强制终止所有名字匹配的进程：

`pkill -9 {{process_name}}`

- 杀死匹配完整命令（而不仅是进程名）的所有进程：

`pkill -9 -f "{{command_name}}"`

- 向特定的进程发送信号 SIGUSR1（用户定义信号1）：

`pkill -USR1 {{process_name}}`

[#]: contributors: ([王兴宇，Linux & BC]，[6 °分离]，[∠( ᐛ 」∠)＿])