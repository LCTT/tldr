# lldb

> LLVM低级调试器

- 调试可执行文件：

`lldb {{executable}}`

- 将 lldb 附加到具有给定 PID 的正在运行的进程：

`lldb -p {{pid}}`

- 等待使用给定程序启动新进程，然后附加到该进程：

`lldb -w -n {{process_name}}`

[#]: contributors: ([Judie]，[Datura stramonium L.])