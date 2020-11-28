# optipng

> PNG 图像文件优化程序

- 使用默认设置压缩 PNG：

`optipng {{path/to/file.png}}`

- 以最佳压缩方式压缩 PNG：

`optipng -o{{7}} {{path/to/file.png}}`

- 以最快的压缩方式压缩 PNG：

`optipng -o{{0}} {{path/to/file.png}}`

- 压缩 PNG 并添加隔行扫描：

`optipng -i {{1}} {{path/to/file.png}}`

- 压缩 PNG 并保留所有元数据（包括文件时间戳）：

`optipng -preserve {{path/to/file.png}}`

- 压缩 PNG 并删除所有元数据：

`optipng -strip all {{path/to/file.png}}`

[#]: contributors: ([Datura stramonium L.])