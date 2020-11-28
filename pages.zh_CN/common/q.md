# q

> 对csv和tsv文件执行类似sql的查询

- 查询 csv 文件，并指定以','作为分隔符：

`q -d',' "SELECT * from {{path/to/file}}"`

- 查询 tsv 文件：

`q -t "SELECT * from {{path/to/file}}"`

- 带标题行的查询文件：

`q -d{{delimiter}} -H "SELECT * from {{path/to/file}}"`

- 从stdin读取数据;查询中的'-'表示来自stdin的数据：

`{{output}} | q "select * from -"`

- 将两个文件(在示例中别名为' f1 '和' f2 ')连接到' c1 '列上，这是一个公共列：

`q "SELECT * FROM {{path/to/file}} f1 JOIN {{path/to/other_file}} f2 ON (f1.c1 = f2.c1)"`

- 使用带有输出头行的输出分隔符格式化输出(注意:命令将基于输入文件头或：

`q -D{{delimiter}} -O "SELECT {{column}} as {{alias}} from {{path/to/file}}"`

[#]: contributors: ([仁人]，[jim.大团结]，[盛曦 姜])