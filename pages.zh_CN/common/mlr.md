# mlr

> Miller和 `awk`, `sed`, `cut`, `join`, and `sort`一样， 用于像CSV, TSV, 和JSON这种经过索引的名称数据

- 采用列表方式美化输出一个 CSV 文件：

`mlr --icsv --opprint cat {{example.csv}}`

- 接收 JSON 数据并漂亮地打印输出：

`echo '{"hello":"world"}' | mlr --ijson --opprint cat`

- 在字段上按字母顺序排序：

`mlr --icsv --opprint sort -f {{field}} {{example.csv}}`

- 按字段的数字降序排序：

`mlr --icsv --opprint sort -nr {{field}} {{example.csv}}`

- 将 CSV 转换为 JSON ，执行计算并显示这些计算：

`mlr --icsv --ojson put '${{newField1}} = ${{oldFieldA}}/${{oldFieldB}}' {{example.csv}}`

- 接收 JSON 并将输出格式化为垂直 JSON ：

`echo '{"hello":"world", "foo":"bar"}' | mlr --ijson --ojson --jvstack cat`

[#]: contributors: ([潘潘]，[爱生活]，[6 °分离]，[玉叶])