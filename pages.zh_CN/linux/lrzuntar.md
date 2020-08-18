# lrzuntar

> 一个用于“lrunzip”的包装器，用于简化目录的解压
> 参见:' lrztar '， ' lrzip '

- 从文件解压缩到当前目录：

`lrzuntar {{path/to/archive.tar.lrz}}`

- 使用特定数量的处理器线程将文件解压缩到当前目录：

`lrzuntar -p {{8}} {{path/to/archive.tar.lrz}}`

- 从文件解压缩到当前目录，并悄悄地覆盖已经存在的项：

`lrzuntar -f {{archive.tar.lrz}}`

- 指定输出路径：

`lrzuntar -O {{path/to/directory}} {{archive.tar.lrz}}`

- 解压后删除压缩文件：

`lrzuntar -D {{path/to/archive.tar.lrz}}`

[#]: contributors: ([仁人]，[王兴宇，Linux 中國])