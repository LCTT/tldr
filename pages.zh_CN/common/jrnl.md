# jrnl

> 命令行简单日志应用程序

- 使用文本编辑器插入新的条目：

`jrnl`

- 快速插入新条目：

`jrnl {{today at 3am}}: {{title}}. {{content}}`

- 显示最后十条：

`jrnl -n {{10}}`

- 查看所有发生在从“去年”的开始到上一个“三月”的开始之间的日志：

`jrnl -from {{"last year"}} -until {{march}}`

- 编辑所有被标记为"texas"和"history"的条目：

`jrnl {{@texas}} -and {{@history}} --edit`

[#]: contributors: ([好名字可以让你的朋友更容易记住你]，[jim.大团结])