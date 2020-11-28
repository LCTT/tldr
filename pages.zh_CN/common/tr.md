# tr

> 转换字符：执行基于单个字符或字符集的替换

- 替换文件中所有出现的某字符，然后打印出结果：

`tr {{find_character}} {{replace_character}} < {{filename}}`

- 替换其他命令输出中出现的所有字符：

`echo {{text}} | tr {{find_character}} {{replace_character}}`

- 将输入内容中匹配字符集1的字符替换成字符集2中对应位置的字符：

`tr '{{abcd}}' '{{jkmn}}' < {{filename}}`

- 将输入内容中所有属于字符集的字符删去：

`tr -d '{{input_characters}}' < {{filename}}`

- 将连续的重复字符压缩成一个字符：

`tr -s '{{input_characters}}' < {{filename}}`

- 将文件中的英文小写字符转换成对应的大写字符：

`tr "[:lower:]" "[:upper:]" < {{filename}}`

- 去掉文件中的非打印字符：

`tr -cd "[:print:]" < {{filename}}`

[#]: contributors: ([Judie]，[顾麒]，[冯伟])