# b2sum

> 计算 BLAKE2 加密校验和

- 计算一个文件的 BLAKE2 校验：

`b2sum {{filename1}}`

- 计算多个文件的 BLAKE2 校验：

`b2sum {{filename1}} {{filename2}}`

- 读取一个包含 BLAKE2 校验值和相应文件名的文件，并校验所有的文件名对应的文件是否匹配相应的校验值：

`b2sum -c {{filename.b2}}`

- 计算标准输入的 BLAKE2 校验值：

`{{somecommand}} | b2sum`

[#]: contributors: ([琳小梁]，[Jack]，[Judie])