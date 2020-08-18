# pandoc

> 对多种文档格式进行相互转换

- 把 markdown 格式文件转换为 pdf 格式（输出文件的格式由其扩展名确定）：

`pandoc {{input.md}} -o {{output.pdf}}`

- 强制使用指定的格式进行转换：

`pandoc {{input.docx}} --to {{markdown_github}} -o {{output.md}}`

- 转换为带有相应格式头部和尾部（headers/footers）的独立文件（LaTeX, HTML, 等等）[否则在使用和编译过程中可能因文件格式不完整而报错]：

`pandoc {{input.md}} -s -o {{output.tex}}`

- 列出全部支持的输入文件格式：

`pandoc --list-input-formats`

- 列出全部支持的输出文件格式：

`pandoc --list-output-formats`

[#]: contributors: ([毕玮])