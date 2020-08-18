# pdftk

> PDF 工具

- 从一个 PDF 文件中提取 1-3、5、6-10 页，并将它们保存为另外一个文件：

`pdftk {{input.pdf}} cat {{1-3 5 6-10}} output {{output.pdf}}`

- 合并（连接）一系列 PDF 文件，并保存为另外一个文件：

`pdftk {{file1.pdf file2.pdf …}} cat output {{output.pdf}}`

- 切分一个 PDF 文件的每一页为一个文件，并按输出模式给与文件名：

`pdftk {{input.pdf}} burst output {{out_%d.pdf}}`

- 顺时针旋转所有页面 180°：

`pdftk {{input.pdf}} cat {{1-endsouth}} output {{output.pdf}}`

- 顺时针旋转第三页 90°，其它页保持不动：

`pdftk {{input.pdf}} cat {{1-2 3east 4-end}} output {{output.pdf}}`

[#]: contributors: ([王興與]，[6 °分离])