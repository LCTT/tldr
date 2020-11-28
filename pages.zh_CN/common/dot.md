# dot

> 一种命令行工具，用于生成有向图的分层绘图

- 根据输入文件名和选定的格式呈现图像文件并确定输出文件名：

`dot -Tpng -O {{path/to/file.dot}}`

- 从 dot 文件创建一个 svg 文件：

`dot -Tsvg -o {{path/to/out_file.svg}} {{path/to/file.dot}}`

[#]: contributors: ([jim.大团结])