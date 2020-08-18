# printf

> 格式化文本并输出

- 打印一条文本消息：

`printf {{"%s\n"}} {{"Hello world"}}`

- 用深蓝色打印整数：

`printf {{"\e[1;34m%.3d\e[0m\n"}} {{42}}`

- 打印浮点数，前缀以 Unicode 的欧元符号（€）：

`printf {{"\u20AC %.2f\n"}} {{123.4}}`

- 打印由环境变量组成的文本消息：

`printf {{"var1: %s\tvar2: %s\n"}} {{"$VAR1"}} {{"$VAR2"}}`

- 将格式化消息存储在变量中（不适用于 zsh ）：

`printf -v {{myvar}} {{"This is %s = %d\n" "a year" 2016}}`

[#]: contributors: ([王兴宇，Linux 中國]，[Datura stramonium L.]，[darksuོn])