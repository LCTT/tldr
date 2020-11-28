# sha512sum

> 计算 SHA512 哈希校验值

- 计算单个文件的 SHA512 哈希校验值：

`sha512sum {{filename1}}`

- 计算多个文件的 SHA512 哈希校验值：

`sha512sum {{filename1}} {{filename2}}`

- 读取包含一个或多个 SHA512 哈希校验值的文件，并校验与之相关的所有文件：

`sha512sum -c {{filename.sha512}}`

[#]: contributors: ([󠀀]，[Thomas Lewis])