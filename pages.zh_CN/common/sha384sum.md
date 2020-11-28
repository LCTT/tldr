# sha384sum

> 计算 SHA384 加密校验值

- 计算一个文件的 SHA384 校验值：

`sha384sum {{filename1}}`

- 计算多个文件的 SHA384 校验值：

`sha384sum {{filename1}} {{filename2}}`

- 读取一个 SHA384 校验值文件，并验证其中列出的文件及其校验值：

`sha384sum -c {{filename.sha384}}`

[#]: contributors: ([硬核老王（📺Linux中国）]，[󠀀])