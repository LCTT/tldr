# unar

> 解压归档/压缩包里的文件内容

- 把压缩包解压到当前目录：

`unar {{archive}}`

- 把归档/压缩包解压到指定目录：

`unar -o {{path/to/directory}} {{archive}}`

- 释放文档时强制覆盖已存在的（同名）文件：

`unar -f {{archive}}`

- 适放文档时如果文件已存在，则自动重命名输出文件：

`unar -r {{archive}}`

- 释放文档时如果文件已存在，则自动跳过：

`unar -s {{archive}}`

[#]: contributors: ([Mr. Ren])