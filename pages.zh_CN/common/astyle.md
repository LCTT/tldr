# astyle

> Ｃ、Ｃ＋＋、Ｃ＃和Ｊａｖａ编程语言的源代码缩进、格式化程序和美化器
> 运行时，将在原始文件名后附加“orig”创建原始文件的副本

- 应用默认样式，每个缩进为 4 个空格，并且不更改格式：

`astyle {{source_file}}`

- 应用附带括号的 Java 样式：

`astyle --style=java {{path/to/file}}`

- 应用带断开大括号的 allman 样式：

`astyle --style=allman {{path/to/file}}`

- 使用空格作为自定义缩进在 2 到 20 个空格之间选择：

`astyle --indent=spaces={{number_of_spaces}} {{path/to/file}}`

- 使用制表符作为自定义缩进在 2 到 20 个之间选择：

`astyle --indent=tab={{number_of_tabs}} {{path/to/file}}`

[#]: contributors: ([-LiaNg-]，[ ]，[󠀀]，[Datura stramonium L.])