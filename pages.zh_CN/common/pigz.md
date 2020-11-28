# pigz

> 多线程 zlib 压缩程序

- 使用默认选项压缩文件：

`pigz {{filename}}`

- 使用最佳压缩方法压缩文件：

`pigz -9 {{filename}}`

- 使用4 个处理器，并不压缩文件：

`pigz -0 -p{{4}} {{filename}}`

- 解压缩文件：

`pigz -d {{archive.gz}}`

- 列出存档的内容：

`pigz -l {{archive.tar.gz}}`

[#]: contributors: ([王興與]，[Datura stramonium L.])