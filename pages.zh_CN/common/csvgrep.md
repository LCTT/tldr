# csvgrep

> 使用字符串和模式匹配过滤 CSV 行
> 包含在 csvkit 中

- 查找第 1 列中具有特定字符串的行：

`csvgrep -c {{1}} -m {{string_to_match}} {{data.csv}}`

- 查找第 3 列或第 4 列与特定正则表达式模式匹配的行：

`csvgrep -c {{3,4}} -r {{regex_pattern}} {{data.csv}}`

- 查找 name 列不包含字符串 John Doe 的行：

`csvgrep -i -c {{name}} -m {{"John Doe"}} {{data.csv}}`

[#]: contributors: ([琳小梁]，[潘潘])