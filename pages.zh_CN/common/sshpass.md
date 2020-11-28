# sshpass

> ssh 密码提供程序
> 它的工作原理是创建一个 TTY，向其中输入密码，然后将 stdin 重定向到 ssh 会话

- 使用文件描述符上提供的密码连接到远程服务器（在本例中为 stdin ）：

`sshpass -d {{0}} ssh {{user}}@{{hostname}}`

- 使用作为选项提供的密码连接到远程服务器，并自动接受未知的 ssh 密钥：

`sshpass -p {{password}} ssh -o StrictHostKeyChecking=no {{user}}@{{hostname}}`

- 使用文件的第一行作为密码连接到远程服务器，自动接受未知的 ssh 密钥，并启动命令：

`sshpass -f {{file}} ssh -o StrictHostKeyChecking=no {{user}}@{{hostname}} "{{command}}"`

[#]: contributors: ([玉叶]，[Datura stramonium L.])