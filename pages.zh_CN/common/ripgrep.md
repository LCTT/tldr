# ripgrep

> 快捷的命令行搜索工具

- 在当前目录和子目录中文件中搜索包含指定模式的行：

`rg {{pattern}}`

- 搜索 .gitignore 文件中忽略的和系统隐藏的文件：

`rg -uu {{pattern}}`

- 仅搜索指定类型的文件（例：html,css 等）：

`rg -t {{filetype}} {{pattern}}`

- 只在目录子集中搜索模式：

`rg {{pattern}} {{set_of_subdirs}}`

- 在匹配的文件中搜索模式（例：README.*）：

`rg {{pattern}} -g {{glob}}`

- 仅列出匹配的文件——在使用管道连接到其它命令时很有用：

`rg --files-with-matches {{pattern}}`

- 显示不匹配指定模式的行：

`rg --invert-match {{pattern}}`

[#]: contributors: ([-]，[jim.大团结])