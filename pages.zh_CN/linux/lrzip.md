# lrzip

> 一个大文件压缩程序
> 参考 `lrunzip`, `lrztar`, `lrzuntar`

- 使用 LZMA 压缩一个文件 - 慢速压缩，快速解压：

`lrzip {{filename}}`

- 使用 BZIP2 压缩文件 - 压缩和速度折中：

`lrzip -b {{filename}}`

- 使用 ZPAQ 压缩文件 - 极致的压缩，但是很慢：

`lrzip -z {{filename}}`

- 用 LZO 压缩 - 轻压缩，解压极快：

`lrzip -l {{filename}}`

- 压缩文件并对其进行密码保护/加密：

`lrzip -e {{filename}}`

- 自定义要使用的处理器线程数：

`lrzip -p {{8}} {{filename}}`

[#]: contributors: ([Datura stramonium L.]，[holy4god])