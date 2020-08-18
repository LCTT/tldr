# base32

> 用 base32 对文件或标准输入（stdin）编码或解码，输出到标准输出（stdout）

- 编码一个文件：

`base32 {{filename}}`

- 解码一个文件：

`base32 -d {{filename}}`

- 从标准输入获取并编码：

`{{somecommand}} | base32`

- 从标准输入获取并解码：

`{{somecommand}} | base32 -d`

[#]: contributors: ([王兴宇]，[Datura stramonium L.])