# parallel

> 让命令并行执行

- 使用所有核，以 gzip 方式一次压缩几个文件：

`parallel gzip ::: {{file1}} {{file2}} {{file3}}`

- 从标准输入读取参数，一次运行 4 个任务：

`ls *.txt | parallel -j4 gzip`

- 使用替换字符串来转换 JPG 图像为 PNG：

`parallel convert {} {.}.png ::: *.jpg`

- 并行处理 xargs，尽可能的将许多参数送给一个命令：

`{{args}} | parallel -X {{command}}`

- 将标准输入分为大小约 1M 的块，然后把每个块发送给一个新命令的标准输入：

`cat {{big_file.txt}} | parallel --pipe --block 1M {{command}}`

- 通过 SSH 在多个机器上运行命令：

`parallel -S {{machine1}},{{machine2}} {{command}} ::: {{arg1}} {{arg2}}`

[#]: contributors: ([航海]，[王兴宇]，[诗翔])