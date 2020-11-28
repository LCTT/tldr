# lrunzip

> 一个用来解压大文件的程序
> 参见 `lrzip`、`lrztar`、`lrzuntar`

- 解压一个文件：

`lrunzip {{filename.lrz}}`

- 用指定数量的处理器线程解压一个文件：

`lrunzip -p {{8}} {{filename.lrz}}`

- 解压文件，如果目标文件存在，则强制覆盖：

`lrunzip -f {{filename.lrz}}`

- 在解压过程中，保留有损坏的文件，而不是删除它：

`lrunzip -K {{filename.lrz}}`

- 指定解文件压名称或路径：

`lrunzip -o {{outfilename}} {{filename.lrz}}`

[#]: contributors: ([王兴宇，Linux & BC]，[Mr. Ren])