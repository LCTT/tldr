# batch

> 稍后当系统负载减轻时执行命令
> atd （或是 atrun ）应该运行，以确保批处理的执行

- 执行从标准输入处输入的命令，按 `Ctrl + D` 退出：

`batch`

- 从系统的标准输入中执行命令：

`echo "{{./make_db_backup.sh}}" | batch`

- 从一个给定的文件中执行命令：

`batch -f {{path/to/file}}`

[#]: contributors: ([潘潘]，[Alan])