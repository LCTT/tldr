# strings

> 在二进制文件中发现可显示字符串

- 打印二进制文件中所有字符串
：

`strings {{file}}`

- 将结果限制为长度至少为length个字符的字符串：

`strings -n {{length}} {{file}}`

- 在每个结果前面加上其位于文件内的偏移量：

`strings -t d {{file}}`

- 将每个结果的前缀与文件中的偏移量以十六进制作为前缀：

`strings -t x {{file}}`

[#]: contributors: ([潘潘]，[Datura stramonium L.]，[jim.大团结])