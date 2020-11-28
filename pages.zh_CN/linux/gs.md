# gs

> GhostScript 是一个 PDF 和 PostScript 解释器

- 查看文件：

`gs -dQUIET -dBATCH {{file.pdf}}`

- 将 PDF 文件大小减少到 150 dpi 图像，以便在电子书设备上读取：

`gs -dNOPAUSE -dQUIET -dBATCH -sDEVICE=pdfwrite -dPDFSETTINGS=/ebook -sOutputFile={{output.pdf}} {{input.pdf}}`

- 将 PDF 文件(第 1 至 3 页)转换为分辨率为 150 dpi 的图像：

`gs -dQUIET -dBATCH -dNOPAUSE -sDEVICE=jpeg -r150 -dFirstPage={{1}} -dLastPage={{3}} -sOutputFile={{output_%d.jpg}} {{input.pdf}}`

- 从 PDF 文件中提取页面：

`gs -dQUIET -dBATCH -dNOPAUSE -sDEVICE=pdfwrite -sOutputFile={{output.pdf}} {{input.pdf}}`

- 合并多个 PDF 文件：

`gs -dQUIET -dBATCH -dNOPAUSE -sDEVICE=pdfwrite -sOutputFile={{output.pdf}} {{input1.pdf}} {{input2.pdf}}`

- 转换 PostScript 文件到 PDF 文件：

`gs -dQUIET -dBATCH -dNOPAUSE -sDEVICE=pdfwrite -sOutputFile={{output.pdf}} {{input.ps}}`

[#]: contributors: ([jim.大团结])