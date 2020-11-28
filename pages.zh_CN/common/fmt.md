# fmt

> 重新格式化文本文件，通过连接文本文件的段落并将行宽限制为给定的字符数（默认为 75 ）

- 重新格式化文件：

`fmt {{path/to/file}}`

- 重新格式化一个文件，生成（最多）`n`个字符的输出行：

`fmt -w {{n}} {{path/to/file}}`

- 重新格式化文件，但不将小于给定宽度的行合并在一起：

`fmt -s {{path/to/file}}`

- 以统一的间距重新格式化文件（单词之间 1 个空格，段落之间 2 个空格）：

`fmt -u {{path/to/file}}`

[#]: contributors: ([潘潘]，[玉叶]，[Datura stramonium L.])