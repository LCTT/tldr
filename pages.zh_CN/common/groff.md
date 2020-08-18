# groff

> 排版程序，读取与格式化命令混合的纯文本并生成格式化输出
> 它是用于文本格式化的 troff 和 nroff Unix 命令的 GNU 替代品

- 将一个 man 页面渲染为普通文本，并显示：

`groff -man -T utf8 {{manpage.1}}`

- 使用 ASCII 输出设备渲染手册页，并使用页显示它：

`groff -man -T ascii {{manpage.1}} | less`

- 将手册页呈现为 HTML 文件：

`groff -man -T html {{manpage.1}} > {{page.html}}`

- 使用 tbl 和 pic 预处理器以及 me 宏集处理 roff 文件：

`groff -t -p -me -T utf8 {{foo.me}}`

- 使用 grog 实用程序猜测的预处理器和宏选项运行  groff 命令：

`eval "$(grog -T utf8 {{foo.me}})"`

[#]: contributors: ([潘潘]，[王兴宇，Linux & BC])