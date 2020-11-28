# zstd

> 用 Zstandard 压缩或解压缩文件

- 将文件压缩为后缀为 .zst 的新文件：

`zstd {{file}}`

- 解压缩一个文件：

`zstd -d {{file}}.zst`

- 解压缩到标准输出（STDOUT）：

`zstd -dc {{file}}.zst`

- 按指定压缩级别压缩文件，0 = 最差，19 = 最佳（默认级别为 3 ）：

`zstd -{{level}} {{file}}`

- 使用更多的内存（压缩和解压缩时）以获得更高的压缩比：

`zstd --ultra -{{level}} {{file}}`

[#]: contributors: ([尚卓燃]，[Datura stramonium L.])