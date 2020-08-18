# mutool

> 转换 PDF 文件，从其中查询信息、抽取数据

- 将文件 1-10 页转换为 10 张 PNG 图片：

`mutool convert -o {{image%d.png}} {{file.pdf}} {{1-10}}`

- 将指定 PDF 文件转换为文字并打印到标准输出：

`mutool draw -F {{txt}} {{file.pdf}} {{2,3,5}}`

- 连接两个 PDF 文件：

`mutool merge -o {{output.pdf}} {{input1.pdf}} {{input2.pdf}}`

- 查询指定 PDF 文件内嵌的所有信息：

`mutool info {{input.pdf}}`

- 从指定 PDF 文件抽取内嵌的所有图片、字体和资源，存入当前文件夹：

`mutool extract {{input.pdf}}`

[#]: contributors: ([李峰])