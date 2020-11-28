# expand

> 将制表符转换为空格

- 将每个文件中的制表符转换为空格，写入标准输出：

`expand {{file}}`

- 将制表符转换为空格，从标准输入读取：

`expand`

- 非空白后不要转换成制表符：

`expand -i {{file}}`

- 设定制表符分开一定数量的字符，而不是 8：

`expand -t={{number}} {{file}}`

- 使用逗号分隔的显式制表符位置列表：

`expand -t={{list}}`

[#]: contributors: ([潘潘]，[启威])