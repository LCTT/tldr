# ps

> 显示运行进程的信息

- 列出当前所有正在运行的进程：

`ps aux`

- 列举所有的进程，并显示完整的命令字符：

`ps auxww`

- 查找匹配指定字符串 string 的进程：

`ps aux | grep {{string}}`

- 列出当前用户的所有进程的全部信息
：

`ps --user $(id -u) -F`

- 以树状形式列出当前用户的所有进程：

`ps --user $(id -u) f`

- 获得进程的父进程 pid：

`ps -o ppid= -p {{pid}}`

[#]: contributors: ([KIP]，[王兴宇]，[wsg]，[Lu]，[Dee.H.Y]，[白宦成]，[~_~小白（）])