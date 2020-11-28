# watch

> 定期执行程序，全屏显示输出

- 持续输出后续命令的结果到屏幕，默认时间间隔2秒：

`watch {{command}}`

- 每隔60秒重新运行某个命令：

`watch -n {{60}} {{command}}`

- 监视目录的内容，突出显示出现的差异：

`watch -d {{ls -l}}`

[#]: contributors: ([Datura stramonium L.]，[# WillxYouNG #])