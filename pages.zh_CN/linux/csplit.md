# csplit

> 把一个文件分成几块
> 这将生成名为 “xx00”、“xx01” 等的文件

- 在第 5 行和第 23 行拆分文件：

`csplit {{file}} {{5}} {{23}}`

- 每 5 行拆分成一个文件（如果总行数不能被 5 整除，则此操作将失败）：

`csplit {{file}} {{5}} {*}`

- 每 5 行拆分成一个文件，忽略精确的除法错误：

`csplit -k {{file}} {{5}} {*}`

- 在第 5 行拆分文件并为输出文件使用自定义前缀：

`csplit {{file}} {{5}} -f {{prefix}}`

- 在与正则表达式匹配的行上拆分文件：

`csplit {{file}} /{{regex}}/`

[#]: contributors: ([玉叶]，[Datura stramonium L.])