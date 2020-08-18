# lp

> 文件打印

- 将命令输出至默认打印机(参考`lpstat` 命令)：

`echo "test" | lp`

- 使用默认打印机打印文件：

`lp {{path/to/filename}}`

- 使用指定打印机打印文件（参考 `lpstat` 命令）：

`lp -d {{printer_name}} {{path/to/filename}}`

- 使用默认打印机打印多份文件（替换数字 N 来打印多份）：

`lp -n {{N}} {{path/to/filename}}`

- 只打印选中的页面（打印第1页，3-5页，第16页）：

`lp -P 1,3-5,16 {{path/to/filename}}`

[#]: contributors: ([6 °分离]，[Mr. Ren])