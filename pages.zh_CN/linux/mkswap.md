# mkswap

> 在一个设备或文件上建立一个 Linux 交换空间

- 把一个分区设置为交换空间：

`sudo mkswap {{/dev/sdb7}}`

- 用一个给定的文件作为交换空间：

`sudo mkswap {{path/to/file}}`

- 在创建交换空间之前检查磁盘分区的坏块：

`sudo mkswap -c {{/dev/sdb7}}`

- 为该文件指定一个卷标（以便 `swapon` 使用该卷标）：

`sudo mkswap -L {{swap1}} {{path/to/file}}`

[#]: contributors: ([王兴宇，Linux & BC]，[Mr. Ren])