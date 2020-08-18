# pdfgrep

> 查询 PDF 文件内容

- 找出 PDF 文件里匹配正则表达式的行：

`pdfgrep {{pattern}} {{file.pdf}}`

- 每个匹配行都包括文件名和页码：

`pdfgrep --with-filename --page-number {{pattern}} {{file.pdf}}`

- 查询文件里以 foo 开头的行，大小写不敏感，返回前三个匹配的行：

`pdfgrep --max-count {{3}} --ignore-case {{'^foo'}} {{file.pdf}}`

- 在当前目录下，递归查找所有 pdf 文件，打印满足指定正则表达式的内容：

`pdfgrep --recursive {{pattern}}`

- 在当前目录下，递归查找所有文件名以 book 结束的 pdf 文件，打印满足指定正则表达式的内容：

`pdfgrep --recursive --include {{'*book.pdf'}} {{pattern}}`

[#]: contributors: ([王興與]，[李峰])