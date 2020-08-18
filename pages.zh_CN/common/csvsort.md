# csvsort

> CSV 文件排序命令
> 包含在 csvkit 中

- 依据第 9 列，对 CSV 文件进行排序：

`csvsort -c {{9}} {{data.csv}}`

- 依据  "name" 列，对 CSV 文件做降序排列：

`csvsort -r -c {{name}} {{data.csv}}`

- 先按第二列、后按第四列，排序 CSV 文件：

`csvsort -c {{2,4}} {{data.csv}}`

- 排序一个 CSV 文件，不推断数据类型：

`csvsort --no-inference -c {{columns}} {{data.csv}}`

[#]: contributors: ([东先生])