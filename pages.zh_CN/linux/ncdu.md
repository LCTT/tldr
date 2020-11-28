# ncdu

> 带ncurses界面的磁盘使用情况分析工具

- 分析当前工作目录：

`ncdu`

- 分析一个给定目录：

`ncdu {{path/to/directory}}`

- 保存结果到文件：

`ncdu -o {{path/to/file}}`

- 排除匹配指定模式的文件，此参数可多次指定以增加更多的匹配模式：

`ncdu --exclude '{{*.txt}}'`

[#]: contributors: ([庄秋彬])