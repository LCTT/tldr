# pycodestyle

> 根据 PEP 8 样式惯例检查 python 代码的工具

- 检查单个文件的代码样式：

`pycodestyle {{file.py}}`

- 检查多个文件的代码样式：

`pycodestyle {{file1.py}} {{file2.py}} {{file3.py}}`

- 仅显示第一次出现的错误：

`pycodestyle --first {{file.py}}`

- 显示每个错误的源代码：

`pycodestyle --show-source {{file.py}}`

- 显示每个错误的特定 PEP 8 文本：

`pycodestyle --show-pep8 {{file.py}}`

[#]: contributors: ([Datura stramonium L.])