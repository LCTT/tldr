# qpdf

> 多样的 PDF 转换软件

- 从一个 PDF 文件中抽取页面 1-3 、5 、6-10 并将它们保存为另一个文件
：

`qpdf --empty --pages {{input.pdf}} {{1-3,5,6-10}} -- {{output.pdf}}`

- 合并一系列 PDF 文件（可指定页面）并将其结果保存为另一个文件：

`qpdf --empty --pages {{file1.pdf}} {{1,6-8}} --pages {{file2.pdf}} {{3,4,5}} -- {{output.pdf}}`

- 按给定的文件名模式将每 n 页一组保存为一个单独的文件：

`qpdf --split-pages=n {{input.pdf}} {{out_%d.pdf}}`

- 以给定的角度旋转一个 PDF 文件中的某些页面：

`qpdf --rotate={{90:2,4,6}} --rotate={{180:7-8}} {{input.pdf}} {{output.pdf}}`

- 从一个密码保护的文件中移除密码：

`qpdf --password={{password}} --decrypt {{input.pdf}} {{output.pdf}}`

[#]: contributors: ([󠀀]，[王兴宇，Linux & BC]，[诗翔])