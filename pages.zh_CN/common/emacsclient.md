# emacsclient

> 打開現有 emacs 服務器中的文件

- 在现有 Emacs 服务器中打开文件（如果可用，使用GUI）：

`emacsclient {{filename}}`

- 在控制台模式下打开文件（没有X窗口）：

`emacsclient -nw {{filename}}`

- 在现有 emacs 框架中打开文件并立即返回：

`emacsclient -n {{filename}}`

[#]: contributors: ([潘潘]，[Judie])