# micro

> Micro是一个现代的并易用的控制台文本编辑器
> 可以使用键盘也可以使用鼠标去浏览和选择文本

- 打开一个文件：

`micro {{file}}`

- 剪切整行：

`Ctrl + K`

- 在文件中正则搜索 (按键 `Ctrl + N`/`Ctrl + P` 去到下一个/前一个匹配)：

`Ctrl + F "{{pattern}}" <Enter>`

- Execute a command
正则搜索：

`Ctrl + E {{command}} <Enter>`

- Perform a substitution in the whole file
执行一条命令：

`Ctrl + E replaceall "{{pattern}}" "{{replacement}}" <Enter>`

- Quit
正则匹配并全部替换：

`Ctrl + Q`

[#]: contributors: ([Ferryman]，[jim.大团结])