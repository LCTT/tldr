# monop

> 查找并显示．ＮＥＴ程序集中的类型和方法的签名

- 显示．ＮＥＴ框架内置类型的结构：

`monop {{System.String}}`

- 列出程序集中的类型：

`monop -r:{{path/to/assembly.exe}}`

- 显示特定程序集中类型的结构：

`monop -r:{{path/to/assembly.dll}} {{Namespace.Path.To.Type}}`

- 仅显示在指定类型中定义的成员：

`monop -r:{{path/to/assembly.dll}} --only-declared {{Namespace.Path.To.Type}}`

- 显示私人成员：

`monop -r:{{path/to/assembly.dll}} --private {{Namespace.Path.To.Type}}`

- 隐藏过时成员：

`monop -r:{{path/to/assembly.dll}} --filter-obsolete {{Namespace.Path.To.Type}}`

- 列出指定程序集引用的其他程序集：

`monop -r:{{path/to/assembly.dll}} --refs`

[#]: contributors: ([ ]，[王兴宇，Linux & BC]，[玉叶])