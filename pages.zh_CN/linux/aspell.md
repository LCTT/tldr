# aspell

> 交互式拼写检查器

- 拼写检查单个文件：

`aspell check {{path/to/file}}`

- 列出标准输入中的拼写错误的单词：

`cat {{file}} | aspell list`

- 显示可用的语言词典：

`aspell dicts`

- 使用不同语言运行 aspell（采用两个字母的 ISO 639 语言代码）：

`aspell --lang={{cs}}`

- 列出标准输入中的拼写错误单词，忽略个人单词列表中的单词：

`cat {{file}} | aspell --personal={{personal-word-list.pws}} {{list}}`

[#]: contributors: ([Datura stramonium L.]，[jim.大团结])