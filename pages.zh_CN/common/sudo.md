# sudo

> 以超级用户或者其他用户的身份去执行一个命令

- 以超级用户的身份运行一个命令：

`sudo {{less /var/log/syslog}}`

- 以超级用户身份使用默认编辑器编辑文件：

`sudo -e {{/etc/fstab}}`

- 以其他用户或其他组的身份运行命令：

`sudo -u {{user}} -g {{group}} {{id -a}}`

- 在上一条命令前添加 `sudo` （只在 bash，zsh 等 shell 中有效）：

`sudo !!`

- 使用超级用户权限启动默认shell：

`sudo -i`

[#]: contributors: ([王兴宇，Linux & BC]，[盛曦 姜]，[Datura stramonium L.])