# pgrep

> 查找或者发送一个信号给指定名称的进程

- 返回匹配命令字符的进程的 PID：

`pgrep {{process_name}}`

- 从包含参数的完整命令行而不仅仅对进程名查找：

`pgrep -f "{{process_name}} {{parameter}}"`

- 从指定用户运行的进程中查找：

`pgrep -u root {{process_name}}`

[#]: contributors: ([王兴宇，Linux 中國]，[holy4god])