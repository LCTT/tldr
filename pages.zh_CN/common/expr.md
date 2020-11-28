# expr

> 用于计算表达式和操作字符串

- 获取字符串长度：

`expr length {{string}}`

- 使用运算符（“ + ”、“ - ”、“ * ”、“ & ”、“ | ”等）计算逻辑表达式或数学表达式应转义特殊符号：

`expr {{first_argument}} {{operator}} {{second_argument}}`

- 获取与“substring”匹配的“string”中第一个字符的位置：

`echo $(expr index {{string}} {{substring}})`

- 提取部分字符串：

`echo $(expr substr {{string}} {{position_to_start}} {{number_of_characters}}`

- 提取字符串中与正则表达式匹配的部分：

`echo $(expr {{string}} : '\({{regular_expression}}\)')`

[#]: contributors: ([Datura stramonium L.])