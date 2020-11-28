# convmv

> 将文件名（不是文件内容）从一种编码转换为另一种编码

- 测试文件名编码转换（不要实际更改文件名）：

`convmv -f {{from_encoding}} -t {{to_encoding}} {{input_file}}`

- 转换文件名编码并将文件重命名为新编码：

`convmv -f {{from_encoding}} -t {{to_encoding}} --notest {{input_file}}`

[#]: contributors: ([Datura stramonium L.])