# awk

> 一种用于文件处理的通用编程语言

- 在以空格分隔的文件中打印第五列（或者说域、字段）：

`awk '{print $5}' {{文件名}}`

- 在以空格分隔的文件中输出所有包含“something”行的第二列：

`awk '/{{something}}/ {print $2}' {{filename}}`

- -F 指定分隔符，使用逗号（而不是空格）作为域分隔符，打印一个文件中每一行的最后一列：

`awk -F ',' '{print $NF}' {{filename}}`

- 对文件第一列的所有值求和并打印总和：

`awk '{s+=$1} END {print s}' {{filename}}`

- 对第一列的值求和并以优美的格式打印值和总和：

`awk '{s+=$1; print $1} END {print "--------"; print s}' {{filename}}`

- 从第一行开始，每隔 3 行进行打印：

`awk 'NR%3==1' {{filename}}`

[#]: contributors: ([琳小梁]，[🐠]，[王兴宇]，[诗翔]，[darksuོn]，[Zxx]，[白宦成])