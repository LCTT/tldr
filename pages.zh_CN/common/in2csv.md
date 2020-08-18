# in2csv

> 将多种制表数据格式转换为 CSV 文件
> 此命令包含在 csvkit 工具集里

- 将指定 XLS 文件转换为 CSV 文件：

`in2csv {{data.xls}}`

- 将 DBF 文件转换为 CSV 文件：

`in2csv {{data.dbf}} > {{data.csv}}`

- 将 XLSX 文件里指定 sheet 转换为 CSV 文件：

`in2csv --sheet={{sheet_name}} {{data.xlsx}}`

- 将指定 JSON 文件通过管道传给 in2csv 转换为 CSV 文件：

`cat {{data.json}} | in2csv -f json > {{data.csv}}`

[#]: contributors: ([李峰])