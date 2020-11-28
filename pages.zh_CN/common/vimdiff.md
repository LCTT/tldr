# vimdiff

> 在 vim 中最多同时打开四个文件并显示
> 有关使用文件和在窗口中导航的信息，请参见 `vim` 文档

- 打开两个文件并显示其不同（最多可打开四个文件做比较）：

`vimdiff {{file1}} {{file2}}`

- 使用水平分栏窗口布局打开两个文件，而不是默认的垂直分栏：

`vimdiff -o {{file1}} {{file2}}`

- 在左右上下窗口间移动光标：

`Ctrl + w {{h|l|k|j}}`

[#]: contributors: ([王兴宇，Linux & BC]，[狷墨居主人]，[Railgun Meta]，[Datura stramonium L.])