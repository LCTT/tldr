# fallocate 

> 为文件保留或释放磁盘空间
> 使用预占的方式分配空间

- 预占700MB的磁盘空间：

`fallocate --length {{700M}} {{path/to/file}}`

- 将已分配的文件缩小200MB：

`fallocate --collapse-range --length {{200M}} {{path/to/file}}`

- 从一个文件的100MB位置缩小20MB：

`fallocate --collapse-range --offset {{100M}} --length {{20M}} {{path/to/file}}`

[#]: contributors: ([CL])