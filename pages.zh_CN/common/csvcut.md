# csvcut

> 过滤、截取 CSV 文件类似 Unix 的 `cut` 命令，但用于处理表格数据
> 此命令包含在 csvkit 工具集里

- 打印出所有列的索引和名称：

`csvcut -n {{data.csv}}`

- 提取第一列和第三列数据：

`csvcut -c {{1,3}} {{data.csv}}`

- 提取除第四列外的所有列数据：

`csvcut -C {{4}} {{data.csv}}`

- 按顺序提取名称为 id 和 first name 的列：

`csvcut -c {{id,"first name"}} {{data.csv}}`

[#]: contributors: ([王兴宇，Linux & BC]，[东先生]，[李峰])