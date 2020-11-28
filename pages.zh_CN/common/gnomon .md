# gnomon 

> 用于使用时间戳注释控制台日志记录语句，并查找缓慢进程的实用程序

- 使用 UNIX（或 DOS ）管道通过 gnomon 管道任何命令的 stdout ：

`{{npm test}} | gnomon`

- 显示自进程启动以来的秒数：

`{{npm test}} | gnomon --type=elapsed-total`

- 以 UTC 显示绝对时间戳：

`{{npm test}} | gnomon --type=absolute`

- 为经过的时间设置 0.5 秒的高阈值，超过时间戳将着色为鲜红色：

`{{npm test}} | gnomon --high {{0.5}}`

- 设置 0.2 秒的中等阈值（时间戳将显示为亮黄色）：

`{{npm test}} | gnomon --medium {{0.2}}`

[#]: contributors: ([潘潘])