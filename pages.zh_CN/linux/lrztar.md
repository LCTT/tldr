# lrztar

> 用于简化目录压缩的“lrzip”包装
> 参考: `tar`, `lrzuntar`, `lrunzip`

- 使用 tar 归档目录，然后压缩：

`lrztar {{path/to/directory}}`

- 与上述相同，ZPAQ-极端压缩，但非常缓慢：

`lrztar -z {{path/to/directory}}`

- 指定输出文件：

`lrztar -o {{path/to/file}} {{path/to/directory}}`

- 覆盖要使用的处理器线程数（省缺值）：

`lrztar -p {{8}} {{path/to/directory}}`

- 强制覆盖现有文件：

`lrztar -f {{path/to/directory}}`

[#]: contributors: ([潘潘]，[Judie]，[墨])