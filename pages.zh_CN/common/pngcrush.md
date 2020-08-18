# pngcrush

> PNG 图片压缩实用工具

- 压缩一个 PNG 文件：

`pngcrush {{in.png}} {{out.png}}`

- 压缩所有的 PNG 文件并输出到目录中：

`pngcrush -d {{path/to/output}} *.png`

- 用全部 114 种可用的算法压缩 PNG 文件，并挑选其中最好的压缩结果：

`pngcrush -rem allb -brute -reduce {{in.png}} {{out.png}}`

[#]: contributors: ([王興與·區塊鏈·Linux中國])