# autoflake

> Python 代码辅助工具，用于移除未使用的导入包和变量

- 移除单个文件中未使用的变量，并显示差异之处：

`autoflake --remove-unused-variables {{file.py}}`

- 移除多个文件中未使用的导入包，并显示不同之处：

`autoflake --remove-all-unused-imports {{file1.py}} {{file2.py}} {{file3.py}}`

- 从文件中移除未使用的变量，重写文件：

`autoflake --remove-unused-variables --in-place {{file.py}}`

- 移除文件夹内所有文件中未使用的变量，重写每一个文件：

`autoflake --remove-unused-variables --in-place --recursive {{path/to/directory}}`

[#]: contributors: ([东先生])