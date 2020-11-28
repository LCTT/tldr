# weasyprint

> 将 HTML 呈现为 PDF 或 PNG
> 主页：<https://weasyprintorg/>

- 将 HTML 文件生成 PDF 文件：

`weasyprint {{path/to/input.html}} {{path/to/output}}.pdf`

- 将HTML文件呈现到PNG，包括附加的用户样式表：

`weasyprint {{path/to/input.html}} {{path/to/output}}.png --stylesheet {{path/to/stylesheet.css}}`

- 呈现时输出附加的调试信息：

`weasyprint {{path/to/input.html}} {{path/to/output}}.pdf --verbose`

- 在输出格式为 PNG 时指定自定义分辨率：

`weasyprint {{path/to/input.html}} {{path/to/output}}.png --resolution {{300}}`

- 为输入HTML文件中的相对URL指定基URL：

`weasyprint {{path/to/input.html}} {{path/to/output}}.png --base-url {{url_or_filename}}`

[#]: contributors: ([0x57ac6e9d]，[情书寄山鬼.]，[王兴宇，Linux & BC]，[Judie])