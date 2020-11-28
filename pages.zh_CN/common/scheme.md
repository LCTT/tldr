# scheme

> MIT Scheme 语言解释器及REPL（交互式 shell）

- 打开一个交互式 shell（REPL）：

`scheme`

- 运行一个 scheme 程序（没有 REPL 输出）：

`scheme --quiet < {{script.scm}}`

- 将一个 scheme 程序装载到 REPL：

`scheme --load {{script.scm}}`

- 装载 scheme 表达式到 REPL：

`scheme --eval {{"(define foo 'x)"}}`

- 以静默模式打开 REPL：

`scheme --quiet`

[#]: contributors: ([王興與·區塊鏈·Linux中國])