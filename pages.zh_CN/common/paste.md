# paste

> 合并文件的行

- 以制表符（TAB）为分隔符，将多行文本合并为一行：

`paste -s {{file}}`

- 使用指定分隔符（delimiter）将多行文本合并为一行：

`paste -s -d {{delimiter}} {{file}}`

- 把两个文件内容每行分别合并在一起，中间用制表符(TAB)为分隔开：

`paste {{file1}} {{file2}}`

- 把两个文件内容每行分别合并在一起，中间用指定的分隔符隔开：

`paste -d {{delimiter}} {{file1}} {{file2}}`

- 以行依次交替的方式合并两个文件：

`paste -d '\n' {{file1}} {{file2}}`

[#]: contributors: ([杨旭东]，[runningwater]，[Yinr]，[0])