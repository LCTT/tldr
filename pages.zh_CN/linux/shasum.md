# shasum

> 计算或检查 SHA 校验和

- 计算一个文件的 SHA1 校验和：

`shasum {{filename}}`

- 计算一个文件的 SHA256 校验和：

`shasum --algorithm 256 {{filename}}`

- 计算多个文件的 SHA512 校验和：

`shasum --algorithm 512 {{filename1}} {{filename2}}`

- 以一个文件作为校验和的结果列表，检查目录下的文件：

`shasum --check {{list_file}}`

- 从标准输入读取并计算 SHA1 校验和：

`{{somecommand}} | shasum`

[#]: contributors: ([王興與·區塊鏈·Linux中國]，[盛曦 姜])