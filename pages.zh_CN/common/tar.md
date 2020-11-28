# tar

> 归档工具
> 通常与压缩工具（如 `gzip` 和 `bzip`）结合使用

- 从文件创建归档：

`tar -cf {{target.tar}} {{file1 file2 file3}}`

- 创建一个压缩的归档：

`tar -czf {{target.tar.gz}} {{file1 file2 file3}}`

- 提取文档至目标文件夹（目录）中：

`tar -xf {{source.tar}} -C {{folder}}`

- 将 gzip 压缩的归档文件提取到当前目录：

`tar -xzf {{source.tar.gz}}`

- 将 bzip 压缩的归档文件提取到当前目录：

`tar -xjf {{source.tar.bz2}}`

- 创建一个压缩的归档文件，使用归档文件后缀来确定使用的压缩程序：

`tar -caf {{target.tar.xz}} {{file1 file2 file3}}`

- 列出归档文件的内容：

`tar -tvf {{source.tar}}`

- 提取与模式匹配的文件：

`tar -xf {{source.tar}} --wildcards {{"*.html"}}`

[#]: contributors: ([王兴宇]，[jim.大团结]，[仁人])