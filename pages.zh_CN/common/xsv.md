# xsv

> 一个 Rust 编写处理 CSV 格式文件的命令行工具

- 查看文件头（通常是列名）：

`xsv headers {{path/to/file.csv}}`

- 统计文件行数：

`xsv count {{path/to/file.csv}}`

- 显示文件概览：

`xsv stats {{path/to/file.csv}} | xsv table`

- 选择若干列：

`xsv select {{column_a,column_b}} {{path/to/file.csv}}`

- 随机显示10行数据：

`xsv sample {{10}} {{path/to/file.csv}}`

- 从一个文件的某列关联到另外一个文件：

`xsv join --no-case {{column_a}} {{path/to/file/a.csv}} {{column_b}} {{path/to/file/b.csv}} | xsv table`

[#]: contributors: ([速溶心]，[王兴宇，Linux 中國]，[holy4god])