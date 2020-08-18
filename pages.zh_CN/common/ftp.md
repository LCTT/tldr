# ftp

> ＦＴＰ服务的客户端交互工具（`译者注：请不要把全角字符替换为半角字符`）

- 连接一个ＦＴＰ服务器（`译者注：请不要把全角字符替换为半角字符`）：

`ftp {{ftp.example.com}}`

- 切换到二进制传输模式（图片、压缩文件等）：

`binary`

- 传输多个文件而不对每个文件进行确认提示：

`prompt off`

- 下载多个文件（通配符表达式）：

`mget {{*.png}}`

- 上传多个文件（通配符表达式）：

`mput {{*.zip}}`

- 删除多个远程服务器上的文件：

`mdelete {{*.txt}}`

- 在远程服务器上重命名一个文件：

`rename {{original_filename}} {{new_filename}}`

[#]: contributors: ([ ]，[王兴宇，Linux & BC]，[玉叶]，[jim.大团结])