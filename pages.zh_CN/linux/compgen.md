# compgen

> 这是条内建在 bash 里的自动补全命令，可以通过连续按两次 TAB 键来调用

- 列出你能运行的所有命令：

`compgen -c`

- 列出所有命令的别名：

`compgen -a`

- 列出你能运行的所有方法：

`compgen -A function`

- 显示 Shell 保留的关键字：

`compgen -k`

- 显示出 ls 适用的所有命令或者别名：

`compgen -ac {{ls}}`

[#]: contributors: ([王兴宇，Linux & BC]，[Mr. Ren]，[程世定])