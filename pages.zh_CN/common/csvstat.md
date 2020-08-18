# csvstat

> 打印 CSV 文件中全部列的描述统计信息
> 包含在 csvkit 中

- 显示所有列的全部状态：

`csvstat {{data.csv}}`

- 显示第二、四列的全部状态：

`csvstat -c {{2,4}} {{data.csv}}`

- 显示所有列的和：

`csvstat --sum {{data.csv}}`

- 显示第三列的最大宽度值：

`csvstat -c {{3}} --len {{data.csv}}`

- 显示 name 列中不重复值的个数：

`csvstat -c {{name}} --unique {{data.csv}}`

[#]: contributors: ([东先生])