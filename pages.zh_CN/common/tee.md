# tee

> 从标准输入一方面打印到屏幕，一方面重定向到文件(或其他命令)

- 复制标准输入到各个文件，同时输出到标准输出：

`echo "example" | tee {{FILE}}`

- 追加内容到给定的文件中，不覆盖原文件：

`echo "example" | tee -a {{FILE}}`

- 把标准输入在输出到终端，并将其传递到另一个程序进行进一步处理：

`echo "example" | tee {{/dev/tty}} | {{xargs printf "[%s]"}}`

- 创建example文件夹并对example计数，同时输出example到终端：

`echo "example" | tee >(xargs mkdir) >(wc -c)`

[#]: contributors: ([Shannon]，[飞龙]，[王兴宇，Linux 中國]，[Johnny.Li])