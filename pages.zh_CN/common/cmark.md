# cmark

> 将 CommonMark Markdown 格式的文本转换为其他格式

- 将 CommonMark Markdown 文件转换为 HTML：

`cmark --to html {{filename.md}}`

- 从标准输入读取数据并转换为 latex：

`cmark --to latex`

- 将直引号（译者注："）转换为弯引号（译者注：”）：

`cmark --smart --to html {{filename.md}}`

- 验证 utf8 字符：

`cmark --validate-utf8 {{filename.md}}`

[#]: contributors: ([Datura stramonium L.])