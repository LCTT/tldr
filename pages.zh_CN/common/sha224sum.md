# sha224sum

> 计算 SHA224 加密校验值

- 计算文件的 SHA224 校验值：

`sha224sum {{filename1}}`

- 计算多个文件的 SHA224 校验值：

`sha224sum {{filename1}} {{filename2}}`

- 读取一个记录 SHA224 校验值的文件，并检查是否所有文件的 SHA224 校验值与记录一致：

`sha224sum -c {{filename.sha224}}`

[#]: contributors: ([󠀀])