# pygmentize

> 基于 Python 的格式高亮器

- 高亮文件格式并输出到标准输出（据文件扩展名推测语言）：

`pygmentize {{file.py}}`

- 使用特别指定的语言来格式高亮：

`pygmentize -l {{javascript}} {{input_file}}`

- 列出可用的词法分析器（用于输入文件的处理器）：

`pygmentize -L lexers`

- 以 HTML 格式保存输出到文件中：

`pygmentize -f html -o {{output_file.html}} {{input_file.py}}`

- 列出可用的输出格式：

`pygmentize -L formatters`

- 输出 HTML 文件，带有附加的格式器选项（全页，行号）：

`pygmentize -f html -O "full,linenos=True" -o {{output_file.html}} {{input_file}}`

[#]: contributors: ([王興與·區塊鏈·Linux中國])