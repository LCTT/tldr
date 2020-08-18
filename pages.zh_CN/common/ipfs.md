# ipfs

> 星际文件系统
> 使 Web 更快、更安全和更开放的一个点对点超媒体协议

- 将文件从本地添加到该文件系统，固定它并打印相对哈希值：

`ipfs add {{filename}}`

- 将文件夹及其文件从本地递归地添加到该文件系统并打印其相对哈希值：

`ipfs add -r {{folder}}`

- 以给定的名字保存一个远程文件，但不固定它：

`ipfs get {{hash}} -o {{filename}}`

- 本地化固定一个远程文件：

`ipfs pin add {{hash}}`

- 显示所有固定的文件：

`ipfs pin ls`

- 从本地存储中取消固定一个文件：

`ipfs pin rm {{hash}}`

- 从本地存储中移除取消固定的文件：

`ipfs repo gc`

[#]: contributors: ([王兴宇，Linux & BC]，[玉叶])