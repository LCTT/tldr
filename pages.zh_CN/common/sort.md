# sort

> 对文本文件行排序

- 对文件进行升序排列：

`sort {{filename}}`

- 对文件以相反的顺序排列：

`sort -r {{filename}}`

- 以不区分大小写的方式对文件排序：

`sort --ignore-case {{filename}}`

- 依照数值大小进行排序：

`sort -n {{filename}}`

- 对passwd文件以：为分隔符进行按照数值大小进行排序：

`sort -t: -k 3n /etc/passwd`

- 去除重复行：

`sort -u {{filename}}`

- 对ls列出的文件以第五列（文件大小）进行排序：

`ls -lh | sort -h -k 5`

[#]: contributors: ([👾]，[∠( ᐛ 」∠)＿]，[jim.大团结])