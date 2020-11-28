# unexpand

> 将空格转换为制表符

- 将每个文件中的空白转换为制表符，并写入标准输出：

`unexpand {{file}}`

- 从标准输入读取，将空白转换为制表符：

`unexpand`

- 转换所有空格，而不仅仅是第一个空格：

`unexpand -a {{file}}`

- 仅转换开头的空格串（覆盖了 -a 参数的作用）：

`unexpand --first-only {{file}}`

- 将指定数量（而不是 8 个）的空格转换为制表符，同时启用 -a 选项：

`unexpand -t {{number}} {{file}}`

[#]: contributors: ([王兴宇，Linux & BC]，[Datura stramonium L.])