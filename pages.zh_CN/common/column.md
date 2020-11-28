# column

> 将标准输入或文件内容格式化为分列显示形式
> 输入文字被分段后，首先填充行，其次填充列，默认分隔符为空格

- 设定输出显示宽度为 30 个字符：

`printf "header1 header2\nbar foo\n" | column -c {{30}}`

- 当使用 `-t` 选项的时候，通过 `-s` 选项指明分割输入文本所用的分隔符，例如分割 csv 文件的时候，应该使用逗号分隔符，默认是空格：

`printf "header1,header2\nbar,foo\n" | column -s{{,}}`

- 自动分列，并对齐到制表位：

`printf "header1 header2\nbar foo\n" | column -t`

- 对分割后的文本，先填充列后填充行，默认先填充行后填充列：

`printf "header1\nbar\nfoobar\n" | column -c {{30}} -x`

[#]: contributors: ([王兴宇，Linux 中國]，[无间狂刀])