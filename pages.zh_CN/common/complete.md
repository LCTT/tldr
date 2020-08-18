# complete

> 为 shell 命令提供参数自动补全功能

- 应用一个对命令执行自动完成的函数：

`complete -F {{function}} {{command}}`

- 将执行自动完成的命令应用于另一个命令：

`complete -C {{autocomplete_command}} {{command}}`

- 应用命令自动补全，但是不会在末尾自动添加空格：

`complete -o nospace -F {{function}} {{command}}`

[#]: contributors: ([潘潘]，[6 °分离]，[Datura stramonium L.])