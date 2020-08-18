# truncate

> 增加或减少文件到指定大小

- 如果指定文件存在将其大小修改为10 GB ，若不存在则新创建大小为 10 GB 的文件：

`truncate -s {{10G}} {{filename}}`

- 将指定文件增大到50M，使用0字节填充：

`truncate -s +{{50M}} {{filename}}`

- 缩减指定文件到2G，删除文件尾部多余数据：

`truncate -s -{{2G}} {{filename}`

[#]: contributors: ([李峰])