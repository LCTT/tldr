# hexdump

> 一个ASCII、十进制、十六进制、八进制转储工具

- 打印文件的十六进制表示形式：

`hexdump {{file}}`

- 以十六进制显示输入偏移量，并在两列中显示其ASCII表示形式：

`hexdump -C {{file}}`

- 显示文件的十六进制表示，但只解释输入的n个字节：

`hexdump -C -n{{number_of_bytes}} {{file}}`

[#]: contributors: ([诗翔]，[Datura stramonium L.])