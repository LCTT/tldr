# screen

> 保持远程服务器上的 会话用一个SSH连接来管理多个窗口

- 创建一个新的 screen 会话：

`screen`

- 自定义名称创建一个新会话：

`screen -S {{session_name}}`

- 新开一个分屏会话并把日志记录在screenlog.x文件中：

`screen -dmLS {{session_name}} {{command}}`

- 显示已打开的分屏会话：

`screen -ls`

- 重新连接一个已打开的分屏会话：

`screen -r {{session_name}}`

- 从分屏会话中断开：

`Ctrl + A, D`

- 杀死一个已断开的分屏会话：

`screen -X -S {{session_name}} quit`

[#]: contributors: ([Shannon]，[王晓田]，[꯭F꯭i꯭n꯭d꯭e꯭r꯭]，[垚])