# latexmk

> 将 LaTeX 源文件编译为已完成的文档
> 需要时自动执行多次运行

- 从每个源编译 dvi（ DeVice 独立文件）文档：

`latexmk`

- 从特定源文件编译 dvi 文档：

`latexmk {{source.tex}}`

- 编译 pdf 文档：

`latexmk -pdf {{source.tex}}`

- 即使存在错误，也强制生成文档：

`latexmk -f {{source.tex}}`

- 清理为特定 tex 文件创建的临时 tex 文件：

`latexmk -c {{source.tex}}`

- 清理当前目录中的所有临时 tex 文件：

`latexmk -c`

[#]: contributors: ([潘潘])