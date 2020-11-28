# od

> 以八进制、十进制或十六进制格式显示文件内容
> 可选择显示字节偏移量和/或每行的可打印表示

- 默认参数展示文件：八进制，每行8字节（译者的wsl上是16字节），八进制字节偏移量，重复行用 * 代替：

`od {{path/to/file}}`

- 详细模式展示文件，例如重复行不用 * 代替：

`od -v {{path/to/file}}`

- 十六进制格式展示文件（每组2字节），偏移量为十进制：

`od --format={{x}} --address-radix={{d}} -v {{path/to/file}}`

- 十六进制格式展示文件（每组1字节），每行4字节：

`od --format={{x1}} --width={{4}} -v {{path/to/file}}`

- 以十六进制格式显示文件及其字符表示形式，并且不打印字节偏移量：

`od --format={{xz}} --address-radix={{n}} -v {{path/to/file}}`

- 从文件的第500字节开始读100个字节：

`od --read-bytes {{100}} --skip-bytes={{500}} -v {{path/to/file}}`

[#]: contributors: ([陈炜]，[AEIOU]，[Datura stramonium L.])