# mkisofs

> 从目录创建ISO文件
> 也称为“genisoimage”

- 从目录创建ISO：

`mkisofs -o {{filename.iso}} {{path/to/source_directory}}`

- 创建ISO时设置光盘标签：

`mkisofs -o {{filename.iso}} -V {{"label_name"}} {{path/to/source_directory}}`

[#]: contributors: ([Judie])