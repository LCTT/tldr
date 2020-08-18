# gunzip

> 从gzip (gz)包释放文件的工具

- 提取文件，如果和已有文件名重复则会替换：

`gunzip {{archive.tar.gz}}`

- 提取文件至一个目标位置：

`gunzip -c {{archive.tar.gz}} > {{archive.tar}}`

- 列出压缩文件中的目录：

`gunzip -l {{file.txt.gz}}`

[#]: contributors: ([6 °分离]，[jim.大团结])