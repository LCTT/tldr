# pdfjoin

> PDF 文件合并工具

- 合并两个 PDF 文件：

`pdfjoin {{file1}} {{file2}} --outfile {{output_file}}`

- 将指定 PDF 的第1页放到其第3到第5页内容后生成新的文件：

`pdfjoin {{file 3-5,1}} --outfile {{output_file}}`

- 将两个 PDF 内的指定内容合并生成新文件：

`pdfjoin {{file1 3-5,1}} {{file2 4-6}} --outfile {{output_file}}`

[#]: contributors: ([李峰])