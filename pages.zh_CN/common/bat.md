# bat

> 打印或者连接文件
> 带有语法高亮显示和集成 Git 的 `cat`

- 将文件内容打印到标准输出：

`bat {{file}}`

- 将多个文件连接输出到目标文件中：

`bat {{file1}} {{file2}} > {{target_file}}`

- 附加几个文件到目标文件中：

`bat {{file1}} {{file2}} >> {{target_file}}`

- 为所有输出行编号：

`bat -n {{file}}`

- 语法高亮显示 json 文件：

`bat --language json {{file.json}}`

- 显示所有支持的语言：

`bat --list-languages`

[#]: contributors: ([琳小梁]，[Datura stramonium L.])