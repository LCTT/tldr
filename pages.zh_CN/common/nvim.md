# nvim

> Neovim 是一个基于 Vim 的程序员文本编辑器，它为不同类型的文本操作提供了多种模式
> 按 ‘i’ 进入编辑模式‘ESC’ 回到正常模式，这不允许常规文本插入

- 打开文件：

`nvim {{file}}`

- 进入文本编辑模式(插入模式)：

`<Esc>i`

- 复制 ("yank") 或剪切 ("delete")  当前行 (用 `P` 粘贴) ：

`<Esc>{{yy|dd}}`

- 撤销最后一次操作：

`<Esc>u`

- 为模式搜索文件 (输入 `n`/`N` 去跳转下一个/前一个匹配)：

`<Esc>/{{search_pattern}}<Enter>`

- 在整个文档中执行正则替换：

`<Esc>:%s/{{pattern}}/{{replacement}}/g<Enter>`

- 保存（写入）文件并退出：

`<Esc>:wq<Enter>`

- 不保存退出：

`<Esc>:q!<Enter>`

[#]: contributors: ([jim.大团结])