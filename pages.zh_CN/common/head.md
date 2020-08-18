# head

> 输出文件的开头部份内容（默认前十行）

- 输出文件的开头部份内容，`-n` 指定输出的行数：

`head -n {{count_of_lines}} {{filename}}`

- 输出文件开始的一些字节：

`head -c {{size_in_bytes}} {{filename}}`

- 输出文件的最后几行以外的所有内容文件的最后几个字节以外的所有内容：

`head -n -{{count_of_lines}} {{filename}}`

- 输出文件中除最后几个字节外的所有内容：

`head -c -{{size_in_bytes}} {{filename}}`

[#]: contributors: ([王兴宇，Linux & BC]，[一笔三画]，[jim.大团结]，[Trekcy])