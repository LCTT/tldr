# enscript

> 将文本文件转换为PostScript、HTML、RTF、ANSI和Overstrikes的工具

- 从文件生成 PostScript 并输出到另一个文件：

`enscript {{path/to/input_file}} --output={{path/to/output_file}}`

- 从文件生成某种输出语言（例如 html ）并输出到另一种语言：

`enscript {{path/to/input_file}} --language={{language}} --output={{path/to/output_file}}`

- 从文件生成 PostScript 并输出到另一个文件，每页 1 到 9 列横向：

`enscript {{path/to/input_file}} --columns={{num}} --landscape --output={{path/to/output_file}}`

- 显示可用的语法突出显示：

`enscript --help-highlight`

- 从文件生成 PostScript 并输出到另一个文件，并使用语法突出显示和指定语言的颜色：

`enscript {{path/to/input_file}} --color=1 --highlight={{language}} --output={{path/to/output_file}}`

[#]: contributors: ([潘潘]，[飞鸿影🌴])