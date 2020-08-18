# gzip

> 用 gzip 压缩解压文件(LZ77)

- 压缩一个文件，生成一个 gzip 格式的文件代替原文件：

`gzip {{file.ext}}`

- 解压文件，还原成原文件未压缩状态：

`gzip -d {{file.ext}}.gz`

- 压缩一个文件，并指定文件名：

`gzip -c {{file.ext}} > {{compressed_file.ext.gz}}`

- 指定文件名解压：

`gzip -c -d {{file.ext}}.gz > {{uncompressed_file.ext}}`

- 指定压缩等级， 1=最快（压缩最低），9=最慢(最好)，默认是6：

`gzip -9 -c {{file.ext}} > {{compressed_file.ext.gz}}`

[#]: contributors: ([Howard])