# touch

> 更改文件的访问及修改时间(atime，mtime)

- 创建新的空文件或将现有文件的时间更改为当前时间：

`touch {{filename}}`

- 将文件的修改时间设置为特定的日期和时间：

`touch -t {{YYYYMMDDHHMM.SS}} {{filename}}`

- 使用第一个文件的最后修改时间设置到第二个文件上：

`touch -r {{filename}} {{filename2}}`

[#]: contributors: ([硬核老王（📺Linux中国）]，[可否具体]，[runoob]，[lonewolf]，[Datura stramonium L.]，[小])