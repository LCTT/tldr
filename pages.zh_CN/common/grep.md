# grep

> (grep＝get regular expression)匹配输入文本中的模式
> 支持简单模式和正则表达式

- 搜索特定字符串：

`grep {{search_string}} {{path/to/file}}`

- 以忽略大小写模式搜索字符串：

`grep -i {{search_string}} {{path/to/file}}`

- 在当前文件夹中递归搜索特定字符串：

`grep -RI {{search_string}} .`

- 使用扩展的正则表达式搜索（支持 `?`、`+`、`{}`、`()`、`|`）：

`grep -E {{^regex$}} {{path/to/file}}`

- 打印匹配字符串附近三行的内容，包括每次匹配的前一行和后一行：

`grep -{{C|B|A}} 3 {{search_string}} {{path/to/file}}`

- 打印每次匹配结果的文件名及对应行数：

`grep -Hn {{search_string}} {{path/to/file}}`

- 使用标准输入（stdin）替代文件：

`cat {{path/to/file}} | grep {{search_string}}`

- 打印不匹配 search_string 的字符串：

`grep -v {{search_string}}`

[#]: contributors: ([Love Your Nature]，[sometimes naive]，[王兴宇]，[YOLO]，[牛祺君]，[我])