# base64

> 对文件或者标准输入进行 Base64 编码或解码，结果输出到标准输出

- 对文件进行 base64 编码：

`base64 {{filename}}`

- 对文件进行 base64 解码：

`base64 -d {{filename}}`

- 对标准输入进行 base64 编码：

`{{somecommand}} | base64`

- 对标准输入进行 base64 解码：

`{{somecommand}} | base64 -d`

[#]: contributors: ([王兴宇]，[刘浩平])