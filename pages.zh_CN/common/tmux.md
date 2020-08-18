# tmux

> 复用几个虚拟主控台

- 创建一个新的 tmux 会话：

`tmux`

- 创建一个新的 tmux 已命名会话：

`tmux new -s {{会话名}}`

- 列出所有会话：

`tmux ls`

- 连接一个会话：

`tmux a`

- 连接一个已命名会话：

`tmux a -t {{会话名}}`

- 脱离会话：

`Ctrl + B, D`

- 结束会话：

`tmux kill-session -t {{会话名}}`

- 结束一个已连接的会话：

`Ctrl + B, x （然后按 `y` 确认）`

[#]: contributors: ([王兴宇]，[꯭F꯭i꯭n꯭d꯭e꯭r꯭])