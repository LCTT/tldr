# case

> 基于表达式的值创建分支

- 匹配字符串变量以决定运行哪个命令：

`case {{$tocount}} in {{words}}) {{wc -w README}}; ;; {{lines}}) {{wc -l README}}; ;; esac`

- 用 “|”表示合并模式， 用 “*”作为回退模式：

`case {{$tocount}} in {{[wW]|words}}) {{wc -w README}}; ;; {{[lL]|lines}}) {{wc -l README}}; ;; *) {{echo "what?"}}; ;; esac`

[#]: contributors: ([东先生])