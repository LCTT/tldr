# sed

> 以一种可编程的方式编辑文本

- 将正则表达式在文件每一行中的第一次出现替换掉，并打印出结果：

`sed 's/{{regex}}/{{replace}}/' {{filename}}`

- 将一个扩展正则表达式在文件中的所有出现替换掉，并打印结果：

`sed -r 's/{{regex}}/{{replace}}/g' {{filename}}`

- 将字符串在文件中的所有出现替换掉，并覆盖原文件（即原位编辑模式）：

`sed -i 's/{{find}}/{{replace}}/g' {{filename}}`

- 只替换匹配行模式的那些行：

`sed '/{{line_pattern}}/s/{{find}}/{{replace}}/' {{filename}}`

- 删除匹配行模式的那些行：

`sed '/{{line_pattern}}/d' {{filename}}`

- 只打印第 n 行至下一个空行之间的文本：

`sed -n '{{line_number}},/^$/p' {{filename}}`

- 对一个文件执行多个查找替换操作：

`sed -e 's/{{find}}/{{replace}}/' -e 's/{{find}}/{{replace}}/' {{filename}}`

- 将分隔符 `/` 换成任何不在查找模式或替换模式中出现的字符，比如 `#`：

`sed 's#{{find}}#{{replace}}#' {{filename}}`

[#]: contributors: ([王興與·區塊鏈·Linux中國]，[Jqs7]，[朱瑛 Ian]，[DD]，[王兴宇]，[darksuོn])