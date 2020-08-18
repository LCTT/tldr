# vim

> VIM（Vi IMproved），一个程序员的文本编辑器，为各种文本操作提供了几种编辑模式
> 按 `i` 进入编辑模式按 `<Esc>` 返回普通模式，该模式下不允许常规文本插入操作

- 打开文件：

`vim {{file}}`

- 进入文本编辑模式（插入模式）：

`<Esc>i`

- 复制（“拉取”）或剪切（“删除”）当前行（按 `P` 粘贴）：

`<Esc>{{yy|dd}}`

- 撤销最后的操作：

`<Esc>u`

- 在文件中搜索一个关键字（按 `n`/`N` 跳至下一个/前一个匹配处）：

`<Esc>/{{search_pattern}}<Enter>`

- 在整个文件中执行一次正则表达式替换：

`<Esc>:%s/{{pattern}}/{{replacement}}/g<Enter>`

- 保存（写入）文件，并退出：

`<Esc>:wq<Enter>`

- 退出而不保存：

`<Esc>:q!<Enter>`

[#]: contributors: ([iDneW]，[王兴宇]，[白宦成]，[Dee.H.Y])