# pdftotext

> 将 PDF 文件转成纯文本格式

- 转换指定 pdf 文件为纯文本并在标志输出打印出来：

`pdftotext {{filename.pdf}} -`

- 将指定 pdf 文件转为纯文本，保存为同名的 txt 文件：

`pdftotext {{filename.pdf}}`

- 转换指定 pdf 文件，保存到指定 txt 文件里：

`pdftotext {{input.pdf}} {{output.txt}}`

- 将 input.pdf 文件的2、3、4页转为纯文本保存到 output.txt ：

`pdftotext -f {{2}} -l {{4}} {{input.pdf}} {{output.txt}}`

[#]: contributors: ([李峰])