# most

> 打开一个或多个文件进行交互式阅读，允许滚动和搜索

- 打开单个文件：

`most {{path/to/file}}`

- 打开多个文件：

`most {{path/to/file1}} {{path/to/file2}}`

- 打开一个文件并从第一行匹配字符串开始显示：

`most {{file}} +/{{string}}`

- 移动打开的文件：

`:O n`

- 跳转到文件第100行：

`{{100}}j`

- 修改当前文件：

`e`

- 把当前窗口平均拆分为两个：

`<CTRL-x> o`

- 退出：

`Q`

[#]: contributors: ([潘潘]，[6 °分离]，[Cuzco])