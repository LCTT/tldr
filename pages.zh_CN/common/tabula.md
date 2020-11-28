# tabula

> 从PDF文件中提取表

- 将所有表从PDF提取到CSV文件：

`tabula -o {{file.csv}} {{file.pdf}}`

- 将所有表从PDF中提取到JSON文件：

`tabula --format JSON -o {{file.json}} {{file.pdf}}`

- 从PDF的第1、2、3和6页中提取表：

`tabula --pages {{1-3,6}} {{file.pdf}}`

- 从PDF的第1页中提取表，猜测要检查页面的哪个部分：

`tabula --guess --pages {{1}} {{file.pdf}}`

- 从PDF中提取所有表，使用折线确定单元格边界：

`tabula --spreadsheet {{file.pdf}}`

- 从PDF中提取所有表，使用空格确定单元格边界：

`tabula --no-spreadsheet {{file.pdf}}`

[#]: contributors: ([仁人])