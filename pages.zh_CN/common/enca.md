# enca

> 检测和转换编码文本文件

- 根据系统的区域设置检测文件的编码：

`enca {{file(s)}}`

- 检测文件编码；-L 选项告诉 enca 当前语言；语言采用 POSIX/C 环境格式，例如 zh_cn、en_US 等：

`enca -L {{language}} {{file(s)}}`

- 文件转换为指定的编码：

`enca -L {{language}} -x {{to_encoding}} {{file(s)}}`

- 将原始文件保存为新文件，并将新文件转换为指定的编码：

`enca -L {{language}} -x {{to_encoding}} < {{original_file}} > {{new_file}}`

[#]: contributors: ([jim.大团结])