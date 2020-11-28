# unzip

> 提取一个 ZIP 压缩包

- 提取zip文件（对于多个文件，按空格分隔文件路径）：

`unzip {{file(s)}}`

- 将zip文件解压缩到给定路径：

`unzip {{compressed_file(s)}} -d {{/path/to/put/extracted_file(s)}}`

- 列出 zip 文件的内容但是不提取：

`unzip -l {{file.zip}}`

- 将文件的内容与提取的文件名一起提取到标准输出（STDOUT）：

`unzip -c {{file.zip}}`

- 提取在 Windows 中创建的 zip 文件，其中包含具有非 ASCII （中文）文件名的文件：

`unzip -O {{gbk}} {{file.zip}}`

[#]: contributors: ([Datura stramonium L.]，[单叔]，[Frederick])