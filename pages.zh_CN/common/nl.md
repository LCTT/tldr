# nl

> 行号工具，应用于文件或标准输入

- 对文件的的非空行编号：

`nl {{file}}`

- 读取标准输出，并显示行号：

`cat {{file}} | nl {{options}} -`

- 仅对可打印字符的行进行编号：

`nl -t {{file}}`

- 对所有行进行编号，包括空行：

`nl -b a {{file}}`

- 仅对行内容匹配基本正则表达式（BRE）的行进行编号：

`nl -b p'FooBar[0-9]' {{file}}`

[#]: contributors: ([王兴宇，Linux & BC]，[玉叶]，[jim.大团结])