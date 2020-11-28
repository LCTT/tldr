# exa

> 一个 `ls` （列出目录内容）的现代替代品

- 按照列数列出文件，每行一个：

`exa --oneline`

- 列出所有文件，包含隐藏文件：

`exa --all`

- 长字符串格式列出所有文件（权限，拥有者，大小和修改时间）：

`exa --long --all`

- 以大小顺序降序列出文件：

`exa --reverse --sort={{size}}`

- 树状关系列出文件，只显示三层目录：

`exa --long --tree --level={{3}}`

- 按照修改时间排序文件列表（时间久的在最前面）：

`exa --long --sort={{modified}}`

[#]: contributors: ([王兴宇，Linux & BC]，[Mr. Ren])