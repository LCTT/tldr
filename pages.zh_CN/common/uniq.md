# uniq

> 去除输入文件中的重复行
> 在去重之前需要先进行排序， 因为只有相邻的重复行才被认为是重复的

- 文件中的重复行只显示一次：

`sort {{file}} | uniq`

- 只显示没有重复的行：

`sort {{file}} | uniq -u`

- 只显示有重复的行：

`sort {{file}} | uniq -d`

- 只显示每一行的出现次数：

`sort {{file}} | uniq -c`

- 显示每行的出现次数，按最频繁排序：

`sort {{file}} | uniq -c | sort -nr`

[#]: contributors: ([winlans]，[单叔])