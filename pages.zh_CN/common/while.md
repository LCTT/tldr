# while

> 简单的shell 循环语句

- 每读取一行标准输入并执行操作：

`while read line; do echo "$line"; done`

- 永久的每秒执行一次命令：

`while :; do {{command}}; sleep 1; done`

[#]: contributors: ([jim.大团结])