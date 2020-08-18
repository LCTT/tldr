# sha1sum

> 计算 SHA1 哈希校验值

- 计算单个文件的 SHA1 校验值：

`sha1sum {{filename1}}`

- 计算多个文件的 SHA1 校验值：

`sha1sum {{filename1}} {{filename2}}`

- 读取一个记录 SHA1 校验值的文件，并检查是否所有文件的 SHA1 校验值与记录一致：

`sha1sum -c {{filename.sha1}}`

[#]: contributors: ([󠀀]，[盛曦 姜])