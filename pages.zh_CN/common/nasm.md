# nasm

> 网际汇编器是一种可移植的x86汇编器

- 默认使用原始文件格式将source.asm文件汇编为名为source的二进制文件：

`nasm {{source.asm}}`

- 使用指定的文件格式将source.asm文件汇编为名为output_file的二进制文件：

`nasm -f {{format}} {{source.asm}} -o {{output_file}}`

- 显示基本nasm命令帮助及支持的输出文件格式：

`nasm -hf`

- 汇编并生成汇编列表文件：

`nasm -l {{list_file}} {{source.asm}}`

- 在汇编操作开始之前将指定目录添加进头文件搜索路径(末尾必须添加斜杠)：

`nasm -i {{/path/to/include_dir/}} {{source.asm}}`

[#]: contributors: ([Thomas Lewis])